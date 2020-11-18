Launch postgresql CLI

`sudo -u postgres psql`

create postgresql database called 'cheat_sheet_development'

`create database cheat_sheet_development;`

add user 'cheater' with an encrypted password 'thief'

`create user cheater with encrypted password 'thief';`

grant privileges on 'cheat_sheet_development' to 'cheater'

`grant all privileges on database cheat_sheet_development to cheater;`
