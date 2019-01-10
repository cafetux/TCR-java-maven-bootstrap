# Un bootstrap pour faire du TCR en java avec Maven

https://medium.com/@kentbeck_7670/test-commit-revert-870bbd756864

écrivez un test qui est censé échouer, puis lancez la commande:

./run.sh -r "message de commit"


Si aucun test n'échoue, le code est reverté. Sinon il est commité

quand vous avez écrit le code qui est censé faire passer le test, lancez:

./run.sh -g "message de commit"


Si un test échoue, vos modification sont effacées (revert), sinon elles sont commitées