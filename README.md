# CA-3---Application-Security---Group-12
Deployment and run instructions:

1. Open WSL
2. cd into your choice of directory
3. Use command: git clone https://github.com/ArchiveBox/ArchiveBox.git
4. cd to ArchiveBox directory
5. Use command: sudo docker-compose up -d
6. Create admin user using command: sudo docker-compose run archivebox manage createsuperuser.
7. Enter username / password, and follow instructions
8. Open web browser and go to: http://127.0.0.1:8000
9. On v0, you will be allowed to view the website as anonymous user.
10. On v1, you will be redirected to a login page for authentication.
11. To stop the running services: sudo docker-compose stop.
12. To start the services again: sudo docker-compose start.
