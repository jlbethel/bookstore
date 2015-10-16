CONTENTS OF THIS FILE
_____________________

*About bookstore
*Configuration and Features
*Usernames and Passwords
*Copyright Information

ABOUT BOOKSTORE
_______________

Bookstore is a Drupal made site for Bart's Bookstore (Embrace the papercut).
The site allows for authenticated users, reviewers, and an admin.
Unauthenticated users are allowed access to the site but with limited available
features. Authenticated users have access to available coupons, and can post
comments to book reviews. Reviewers have the same rights as authenticated users
and the ability post book reviews. The site administrator has full access to
the site and all developer options.

CONFIGURATION AND FEATURES
__________________________
(For macs)

Clone https://github.com/jlbethel/bookstore.git to your desktop. Run MAMP and
point the server to the bookstore directory. Bring up phpMyAdmin in your browser
by typing "localhost/phpmyadmin". Import the bookstore_database from
"bookstore/sites/db_backup/bookstore_database.sql.zip". Create a user by
clicking the "privileges" tab. Set the username to "admin" and the password to
"root". In another tab of your browser, navigate to "http://localhost:8888/"
and enjoy the site!

USERNAMES AND PASSWORDS
_______________________
MySql:

Username: admin
Password: root

Drupal:

Administrator
Username: bookstore_admin
Password: password

Reviewer
Username: reviewer1
Password: password

Authenticated User
Username: jlbethel
Password: password

COPYRIGHT INFORMATION
_____________________
Copyright (c) 2015 Jason Bethel

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to
do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
