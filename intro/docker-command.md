docker pull images_name:images_tag
docker images
docker rmi <image_id>

docker run  --name name_container name_image
docker run name_image (a random name will be generated)
(add -it to provide an interactive terminal tty)

docker ls (to show running container only)
docker ls -a  (to show all containers)

docker start name-or-id
docker container start name-or-id
docker stop name-or-id
docker container stop name-or-id
docker restart name-or-id
docker container restart name-or-id

docker exec name-or-id command
(add -it to provide an interactive terminal tty)

docker rm name_container
docker rename old_name new_name


docker logs name_or_id_container


See 'docker container --help'.

Usage:  docker container COMMAND

Manage containers

Commands:
  attach      Attach local standard input, output, and error streams to a running container
  commit      Create a new image from a container's changes
  cp          Copy files/folders between a container and the local filesystem
  create      Create a new container
  diff        Inspect changes to files or directories on a container's filesystem
  exec        Execute a command in a running container
  export      Export a container's filesystem as a tar archive
  inspect     Display detailed information on one or more containers
  kill        Kill one or more running containers
  logs        Fetch the logs of a container
  ls          List containers
  pause       Pause all processes within one or more containers
  port        List port mappings or a specific mapping for the container
  prune       Remove all stopped containers
  rename      Rename a container
  restart     Restart one or more containers
  rm          Remove one or more containers
  run         Create and run a new container from an image
  start       Start one or more stopped containers
  stats       Display a live stream of container(s) resource usage statistics
  stop        Stop one or more running containers
  top         Display the running processes of a container
  unpause     Unpause all processes within one or more containers
  update      Update configuration of one or more containers
  wait        Block until one or more containers stop, then print their exit codes
