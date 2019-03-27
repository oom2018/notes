```shell
rake docker:clean
rake db:create
rake service:all
```
```text
lixy@zypc1:~/src/github.com/rubykube/microkube$ rake -T
rake db:console                       # Database Console
rake db:create                        # Create database
rake db:drop                          # Drop all databases
rake db:load                          # Load database dump
rake docker:clean                     # Clean up all docker volumes
rake docker:down                      # Stop all runnning docker contrainers
rake geth:import                      # [Optional] Import etherium blockchain data
rake payload:send[service,image,url]  # Generate JWT
rake render:config                    # Render configuration and compose files and keys
rake service:all[command]             # Run the micro app with dependencies (does not run Optional)
rake service:app[command]             # Run mikro app (barong, peatio)
rake service:arke[command]            # [Optional] Run arke
rake service:backend[command]         # Run backend (vault db redis rabbitmq)
rake service:cryptonodes[command]     # [Optional] Run cryptonodes
rake service:daemons[command]         # [Optional] Run peatio daemons (ranger, peatio daemons)
rake service:frontend[command]        # Run the frontend application
rake service:proxy[command]           # Run Traefik (reverse-proxy)
rake service:setup[command]           # Run setup hooks for peatio and barong
rake service:tower[command]           # Run the tower application
rake service:utils[command]           # [Optional] Run utils (postmaster)
rake terraform:apply                  # Apply the Terraform configuration
rake terraform:destroy                # Destroy the Terraform infrastructure
rake terraform:init                   # Initialize the Terraform configuration
rake toolbox:run                      # Run the toolbox
rake vendor:clone                     # Clone the frontend apps repos into vendor/
```
