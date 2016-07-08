#devops && micro-serviços

*dicas e considerações*

---

micro-serviços: agilidade

---

micro-serviços: gestalt

---

...*mas problemas complexos seguem complexos*

---

como podemos...

* testar?
* versionar?
* deployar?
* monitorar?
* debugar?

---

testes: [considere mais testes de serviço](https://www.mountaingoatsoftware.com/blog/the-forgotten-layer-of-the-test-automation-pyramid)

---

testes: use testes de integração de serviços

---

testes: considere automação de post-deployment checks

---

testes: segregue a execução de testes

---

versionamento: [use semVer](http://semver.org/)

---

testes/versionamento: [consumer-driven contracts](http://martinfowler.com/articles/consumerDrivenContracts.html)

---

deploy: comece com um monolito

---

deploy: [github flow](https://guides.github.com/introduction/flow/) > [gitflow](http://nvie.com/posts/a-successful-git-branching-model/)

---

deploy: [blue/green](http://martinfowler.com/bliki/BlueGreenDeployment.html)

---

monitoramento: APM

---

monitoramento: health checks ([jidoka](http://blog.toyota.co.uk/jidoka-toyota-production-system))

---

debugging: [status codes *com significado*](http://jsonapi.org/)

---

debugging: log aggregation & [correlação de eventos](https://en.wikipedia.org/wiki/Event_correlation)

---

dica: [12-factor](http://12factor.net/)

---

dica: [reactive manifesto](http://www.reactivemanifesto.org/)

---

tks