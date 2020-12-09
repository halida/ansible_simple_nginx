halida.simple_nginx
=========

Example
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
    - roles:
      - role: halida.simple_nginx
        ssl:
          - name: example.com
            crt: '../ssl/example.com/server.crt'
            key: '../ssl/example.com/server.key'
            dhparam: '../ssl/example.com/dhparam.pem'
        apps:
          - name: airsonic
            host: airsonic.example.com
            port: 4040
            ssl: example.com


License
-------

BSD

Author
------------------

linjunhalida@gmail.com

