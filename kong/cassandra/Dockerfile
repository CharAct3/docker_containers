# Cassandra
FROM cassandra:3.10

RUN sed -i "s|cluster_name: 'Test Cluster'|cluster_name: 'Staging DB'|g" /etc/cassandra/cassandra.yaml
RUN sed -i "s|authenticator: AllowAllAuthenticator|authenticator: PasswordAuthenticator|g" /etc/cassandra/cassandra.yaml

