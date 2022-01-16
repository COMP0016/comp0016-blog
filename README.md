# Live server

http://students.cs.ucl.ac.uk/2021/group38/

# Test server

Run from the root of the project
```bash
python3 -m http.server
```

Open in your browser http://localhost:8000/2021/group38/

# Deployment

- Use ThinLinc client to connect to UCL network
- Applications > System Tools > Guake Terminal
- Press F12
- `cd Documents/comp0016-blog`
- `git pull`
- Open 2 windows of the file explorer
- In 1 window open `/cs/student/www/2021/group38` and delete the contents
- In the other window open `Documents/comp0016-blog/2021/group38`
- Copy the contents of `Documents/comp0016-blog/2021/group38`, into `/cs/student/www/2021/group38`
- Back in the terminal, `cd /cs/student/www/2021/group38`
- Change permissions on files `find . -type f -exec chmod 664 {} \;`
- Change permissions on folders `find * -type d -exec chmod 775 {} \;`
