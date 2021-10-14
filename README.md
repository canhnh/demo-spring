# Spring Boot JPA MySQL - Building Rest CRUD API example
#Init project demo

## init git
git init
## add to git
git add .
## commit code
git commit -m "first commit"
## add to git remote
git remote add origin http://192.168.8.159/root/project-demo.git

## Run Spring Boot application
```
mvn spring-boot:run
```

**Register some users with /signup API:**
# 
![alt text](https://www.bezkoder.com/wp-content/uploads/2019/10/spring-boot-authentication-jwt-spring-security-signup-mod.png)

**Access public resource:** GET /api/test/all
# 
![alt text](https://www.bezkoder.com/wp-content/uploads/2019/10/spring-boot-authentication-jwt-spring-security-get-public-resource.png)

**Access protected resource:** GET /api/test/user
# 
![alt text](https://www.bezkoder.com/wp-content/uploads/2019/10/spring-boot-authentication-jwt-spring-security-get-user-resource-unauthorized.png)

**Login an account:** POST /api/auth/signin
# 
![alt text](https://www.bezkoder.com/wp-content/uploads/2019/10/spring-boot-authentication-jwt-spring-security-login-mod.png)

**Access ROLE_USER resource:** GET /api/test/user
# 
![alt text](https://www.bezkoder.com/wp-content/uploads/2019/10/spring-boot-authentication-jwt-spring-security-get-user-resource.png)

R**OLE_MODERATOR resource:** GET /api/test/mod
# 
![alt text](https://www.bezkoder.com/wp-content/uploads/2019/10/spring-boot-authentication-jwt-spring-security-get-mod-resource.png)

**Access ROLE_ADMIN resource:** GET /api/test/admin
# 
![alt text](https://www.bezkoder.com/wp-content/uploads/2019/10/spring-boot-authentication-jwt-spring-security-get-admin-resource-unauthorized.png)

