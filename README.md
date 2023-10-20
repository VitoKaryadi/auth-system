# Auth Key 

<img src="https://github.com/VitoKaryadi/auth-system/blob/main/README%20ASSETS/authkey.png" align="right"
     alt="AuthKey Logo" width="120">

AuthKey is a security system designed for your website needs, AuthKey is created using PHP!

* Easy AuthKey application.
* An open source programming project
* User data is properly encrypted,
  passwords cannot be seen by admin
* AuthKey does not retrieve data other than the data requested
  in the form and the user has agreed

<p align="center">
  <img src="https://github.com/VitoKaryadi/auth-system/blob/c39d49decddcce1680c9093e7a842276b78290ad/README%20ASSETS/Screenshot%202023-10-20%20191914.png?raw=true" alt="AuthKey System" width="738">
</p>

## How to install AuthKey (Windows)

1. Download/Clone this repository [Download Here!](https://github.com/VitoKaryadi/auth-system/archive/refs/heads/main.zip)
2. Place AuthKey Folder in Directory `C:\xampp\htdocs\AuthKey`
3. Start Apache & MySQL on XAMPP
4. Open phpMyAdmin `http://127.0.0.1/phpmyadmin`
5. Create new database; give name _authsystem_
6. Go to SQL Menu, then create new Table with this query:
   ```sql
     CREATE TABLE IF NOT EXISTS `users` (
      `id` int(11) NOT NULL AUTO_INCREMENT,
      `displayname` varchar(50) NOT NULL,
      `username` varchar(50) NOT NULL,
      `email` varchar(50) NOT NULL,
      `password` varchar(50) NOT NULL,
      `create_datetime` datetime NOT NULL,
      PRIMARY KEY (`id`)
     );
   ```
   <p align="center">
        <img src="https://github.com/VitoKaryadi/auth-system/blob/main/README%20ASSETS/Screenshot%202023-10-20%20200211.png" alt="SQL Query" width="738">
   </p>
7. Open Browser then browse `http://127.0.0.1/AuthKey`

## Report Problem

Bugs | Problem | Suggestion
`Coming Soon!`

## Donate

* Trakteer.id
* QRIS
