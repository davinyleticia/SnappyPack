# SnappyInstall

Setup de Ferramentas para Desenvolvedores

Este projeto oferece um script em Bash que automatiza a instalação de ferramentas essenciais para um ambiente de desenvolvimento em sistemas Linux (baseados em Debian/Ubuntu). O script instala editores de código, navegadores, gerenciadores de banco de dados e outras utilidades importantes para desenvolvedores.

<img class="mascote" src='http://snappyinstall.codes/img/mascote.png'/>

## Ferramentas Instalados ( Pacote dev )

O script instalará as seguintes ferramentas:

- **Visual Studio Code**: Editor de código da Microsoft, altamente popular entre desenvolvedores.
- **Google Chrome**: Navegador de internet.
- **Insomnia REST**: Ferramenta para teste de APIs REST.
- **Git**: Sistema de controle de versões.
- **NVM**: Node Version Manager, para gerenciar versões do Node.js.
- **DBeaver**: Cliente de banco de dados universal.
- **FileZilla**: Cliente FTP.
- **OBS Studio**: Software de gravação de tela e transmissão ao vivo.
- **Raspberry Pi Imager**: Ferramenta de gravação de sistema para cartões SD e drives USB.

## Pré-requisitos

Para rodar o script, é necessário:

- **Sistema Operacional**: Ubuntu, Debian, ou qualquer distribuição Linux baseada em `apt`.
- **Privilégios de Superusuário**: Execute o script com `sudo` para permitir a instalação dos pacotes.

## Como Usar

Você pode executar o script diretamente usando o comando `curl`:

```bash
curl -sSL snappyinstall.codes/dev | sudo bash
```

Este comando baixa e executa o script diretamente, garantindo uma instalação rápida e sem a necessidade de baixar o arquivo manualmente.

## Estrutura do Script

O script segue a seguinte estrutura:

1. **Verificação de Permissões**: Confirma que o usuário possui privilégios `sudo`.
2. **Atualização do Sistema**: Atualiza o sistema para evitar conflitos na instalação.
3. **Instalação das Ferramentas**: Baixa e instala cada ferramenta, utilizando `apt` ou arquivos `.deb`, quando necessário.
4. **Limpeza**: Remove arquivos temporários baixados, como pacotes `.deb`.

## Solução de Problemas

- **Erro de Permissão**: Certifique-se de executar o script com `sudo`.
- **Dependências Faltantes**: Durante a execução, o `apt` pode solicitar a instalação de dependências adicionais para algumas ferramentas.
- **Distribuição Não Suportada**: Este script é feito para sistemas baseados em `apt`. Distribuições como Fedora ou Arch Linux precisarão de adaptações no script.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## Licença

Este projeto é licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.


## Contribuidores 🤝

Agradecemos a todos que contribuem para este projeto! 🎉

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/davinyleticia">
        <img src="https://avatars.githubusercontent.com/davinyleticia" width="200px;" height="203px" alt="Foto do Contribuidor"/><br>
        <sub><b>Daviny Letícia</b></sub>
      </a><br>
      🚀 Fundadora
    </td>
    

  </tr>
</table>


---

### Observação

Este script instala as ferramentas mais utilizadas em ambientes de desenvolvimento. Para configurações adicionais ou mais específicas, consulte a documentação oficial de cada ferramenta.


