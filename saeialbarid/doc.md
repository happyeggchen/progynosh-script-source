saeialbarid
============
    A tool to communicate through tcp and unix socket
      Include:
        6 functions
          {client-stcp,client-uset,listen-stcp,listen-uset,help_echo,main}
      Usage:
        s argv[2] (serve a api server)
          -Available:
            uset argv[3]
              Communicate through unix socket
                argv[3]:socket location,default is /tmp/saeialbarid.sock
        -----------------------------------------------
            stcp argv[3] argv[4]
              Communicate through tcp
                argv[3]:Tcp listen addr,default is 127.0.0.1/32
                argv[4]:Tcp listen port,default is 8080
        -----------------------------------------------
        c argv[2] (client a api server)
          -Available:
            uset argv[3]
              Communicate through unix socket
                argv[3]:socket location,default is /tmp/saeialbarid.sock
        -----------------------------------------------
            stcp argv[3] argv[4]
              Communicate through tcp
                argv[3]:Tcp listen addr,default is 127.0.0.1
                argv[4]:Tcp listen port,default is 8080"
