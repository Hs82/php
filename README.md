PHPを使ったページング機能

html/css
php/mysql(php 5.2)
正規表現



データベース作成：

create database test;
grant all on test.* to test@localhost identified by 'root';

create table comments (
    id int not null auto_increment primary key,
    comment text,
    create datatime,
    modified datatime
);

insert into comments (comments, created, modified) values
('nomment1', now(),now()),
('comment2', now(), now()),
('comment3', now(), now());



create a new repository on the command line

echo "# php" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Hs82/php.git
git push -u origin master

or push an existing repository from the command line

git remote add origin https://github.com/Hs82/php.git
git push -u origin master


