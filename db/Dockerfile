#使うDockerイメージ
FROM postgresql 

#ポートを開ける
EXPOSE 3306

#MySQL設定ファイルをイメージ内にコピー
ADD ./my.cnf /etc/mysql/conf.d/my.cnf

#docker runに実行される
# CMD ["postgresqld"]
# RUN ["mysqld"]