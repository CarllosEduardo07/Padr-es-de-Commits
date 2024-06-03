# Semantic Commit Messages

Veja como uma pequena mudança no estilo da sua mensagem de commit pode torná-lo um programador melhor.

Format: `<type>(<scope>): <subject>`

`<scope>` is optional

## Example

```
feat: add hat wobble
^--^  ^------------^
|     |
|     +-> Summary in present tense.
|
+-------> Type: chore, docs, feat, fix, refactor, style, or test.
```

More Examples:

- `feat`: (novo recurso para o usuário, não um novo recurso para script de construção)
- `fix`: (correção de bug para o usuário, não uma correção para um script de construção)
- `docs`: (alterações na documentação)
- `style`: (formatação, falta de ponto e vírgula, etc; nenhuma alteração no código de produção)
- `refactor`: (refatorando o código de produção, por exemplo. renomeando uma variável)
- `test`: (adição de testes ausentes, refatoração de testes; nenhuma alteração no código de produção)
- `chore`: (atualizando tarefas pesadas, etc; nenhuma alteração no código de produção)

Referências:

- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html
