# Apache_Superset_Installation_steps
Apache Superset is an open-source data visualization platform that allows us to create interactive dashboards.

git clone https://github.com/apache/superset.git

cd superset

git checkout 2.1.0


vi docker-compose-non-dev.yml
>> x-superset-image: &superset-image apache/superset:2.1.0


docker compose -f docker-compose-non-dev.yml pull

docker compose -f docker-compose-non-dev.yml up
