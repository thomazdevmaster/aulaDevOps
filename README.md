# Exercício 1
1. No terminal execute `docker container run -it ubuntu /bin/bash`
2. Em seguida, no terminal do container `apt update -y && apt install curl -y && curl --version`

---

# Exercício 2
1. Dockerfile criado para a aplicação
2. execute `docker build -t teste .`
3. execute `docker container run -d -p 3000:3000 teste`
4. para testar o endpoint `curl localhost:3000`