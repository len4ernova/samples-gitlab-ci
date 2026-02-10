gitlab-ci.yaml - конвеер встраивался в проект C++ ( ![Pipeline C++ project](combi_1.png) ). 
Состоит из:
- компонеты:
    + cppcheck 
    + semgrep secret
    + sonarqube
    + defectdojo
    + osv
- явно прописанные jobs:
    + buil
    + manual-test
    + coverage
    + fuzz
