cd /home/ubuntu/test/angular8-crud-demo/src/environments
vi environment.ts
```
export const environment = {
  production: false,
  baseUrl: 'https://angular.vvcekarthik.tk'

};
```
cd /home/ubuntu/test/angular8-crud-demo
docker build -t gookarthik/angular-spring-mysql:angualr .

docker images
docker tag ed7b12b0fb17 gookarthik/angular-spring-mysql:angualr
docker push gookarthik/angular-spring-mysql:angualr

cd /home/ubuntu/karthik-use/test/angular8-crud-demo
kubectl apply -f deployment.yml
