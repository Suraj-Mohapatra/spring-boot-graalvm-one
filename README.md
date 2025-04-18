# spring-boot-graalvm-one
this is a spring boot maven project that native compiles the project using GraalVM

git clone https://github.com/Suraj-Mohapatra/spring-boot-graalvm-one.git

cd .\spring-boot-graalvm-one

mvn -Pnative native:compile -DskipTests

buidling takes substantial amount of time. AFter building runt the executable generated inside /target directory.