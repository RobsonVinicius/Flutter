<div align="center">

## Executando o projeto no IntelliJ

</div>

Agora vamos abrir o projeto no IntelliJ, como primeiro passo, feche o prompt ou terminal que foi usado para abrir o emulador e executar o projeto.

Em seguida, abra o IntelliJ e na tela de launcher escolha a opção **Open** e selecione o diretório do projeto criado pelo Flutter e clique em **OK**. Aguarde o IntelliJ finalizar todas as tarefas para configurar o projeto.

Após o IntelliJ finalizar todas as tasks, abra o emulador pelo IntelliJ selecionando o emulador disponível por meio do campo combobox/select ao lado do combobox que indica **main.dart**. Ao apresentar o emulador, execute o arquivo **main.dart** e verifica se apresenta o App da mesma maneira que foi apresentado via prompt/terminal.

Modifique o código para que apresente apenas o texto `'Bem vindo ao Projeto'` com o Widget `Text`. Nesta modificação, apague todo o código que foi gerado automaticamente, deixando apenas o seguinte trecho:

```
void main() => runApp();
```

Então adiciona o `Text()` dentro do `runApp` enviando a `String` via argumento. Lembre-se de configurar o TextDirection para evitar o problema de execução. Teste o App e veja se apresenta a tela esperada.