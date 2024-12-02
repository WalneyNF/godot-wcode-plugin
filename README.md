# wCode - Godot Plugin

O **wCode** é um plugin inovador para o **Godot Engine** que visa acelerar e simplificar o processo de desenvolvimento de código. Ele permite aos desenvolvedores inserir rapidamente estruturas de código comuns (como loops, condicionais e funções) diretamente no editor, sem a necessidade de digitação manual.

## Funcionalidades principais:

- **Acelere sua codificação**: Insira blocos de código com apenas um clique, economizando tempo e reduzindo erros de digitação.
- **Personalização de Snippets**: Adicione ou modifique facilmente novos snippets através do arquivo `snippets.json`, permitindo a personalização do comportamento do plugin.
- **Menu Dinâmico**: O plugin lê automaticamente o conteúdo do arquivo JSON e exibe as opções no menu do Godot, facilitando a expansão com novos comandos sem a necessidade de reconfigurar o plugin.
- **Facilidade de uso**: Sistema intuitivo de snippets projetado tanto para iniciantes quanto para desenvolvedores experientes, garantindo um fluxo de trabalho mais eficiente.

## Instalação

1. Faça o **download** ou **clone** do repositório.
2. Copie a pasta `addons/wcode` para o diretório `res://addons/` dentro do seu projeto Godot.
3. Abra o Godot, vá para **Projeto > Configurações de Plugins** e ative o **wCode**.
4. Após habilitar o plugin, vá para **Projeto > Ferramentas** e escolha **wCode**.
5. Selecione o arquivo `snippets.json` de sua preferência e o plugin carregará os snippets.
6. Agora, no menu **Projeto > Ferramentas**, abaixo de **wCode**, aparecerão os snippets carregados.

## Como adicionar novos Snippets

1. Abra o arquivo `snippets.json` localizado em `addons/wcode/`.
2. Adicione ou edite os snippets conforme desejado. O formato do arquivo deve ser:

    ```json
    [
      {
        "name": "Nome do Snippet",
        "code": "Código do snippet aqui"
      }
    ]
    ```

3. Salve o arquivo. O plugin irá atualizar automaticamente a lista de snippets no menu.

## Contribuições

Se você quiser contribuir para o desenvolvimento deste plugin ou adicionar novos recursos, fique à vontade para **forkar** o repositório e abrir **pull requests**.

## Suporte

Caso precise de ajuda ou tenha alguma sugestão, entre em contato por e-mail: [walneyk@hotmail.com](mailto:walneyk@hotmail.com).

---

Ideal para desenvolvedores que buscam otimizar sua produtividade ao programar em **Godot Engine**, especialmente em jogos 2D e 3D, onde estruturas repetitivas de código são frequentemente utilizadas.
