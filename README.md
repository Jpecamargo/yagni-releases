<p align="center">
  <img src="icon.png" width="128" height="128" alt="Ícone do Yagni">
</p>

<h1 align="center">Yagni</h1>

<p align="center">
  Mede a qualidade de um repositório segundo o Extreme Programming — e junta, numa janela só,
  o terminal com o Claude, o navegador e os apps de cada projeto.
</p>

<p align="center">
  <a href="https://github.com/Jpecamargo/yagni-releases/releases/latest"><b>Baixar a versão mais recente</b></a>
</p>

Este repositório guarda só os instaladores e o arquivo que o app consulta para se atualizar.
O código-fonte é privado.

## O que o Yagni faz

- **Análise do repositório**, sem IA e sem enviar código para fora: complexidade, tamanho,
  duplicação, test smells e o que foge do padrão do próprio projeto, organizados pelos tópicos
  de XP, commit a commit.
- **Dashboard e Smells**: pilares, tendência, piores pontos e a lista de achados com o trecho do
  código.
- **Workspace por projeto**: painéis com tiling e autotiling, terminal que já abre o Claude Code
  na pasta do projeto, navegador embutido e apps externos presos aos painéis (macOS).
- **Linguagens**: TypeScript/JavaScript, Python, Rust, Go e Swift.

## Instalar

| Sistema | Arquivo | Observação |
| --- | --- | --- |
| macOS (Apple Silicon) | `Yagni_<versão>_aarch64.dmg` | O app não é assinado pela Apple: na primeira vez, clique com o botão direito em **Yagni** › **Abrir** (ou libere em Ajustes › Privacidade e Segurança). |
| Windows | `Yagni_<versão>_x64-setup.exe` | O SmartScreen pode avisar no primeiro uso: **Mais informações** › **Executar assim mesmo**. |
| Linux | `Yagni_<versão>_amd64.AppImage` | `chmod +x` e execute. O `.deb` também é publicado, mas só o AppImage se atualiza sozinho. |

## Atualizações

O Yagni instalado procura versões novas 15 segundos depois de abrir e a cada 6 horas. Quando há
uma, aparece **"Atualização disponível"** na barra lateral; em **Configurações › Sobre** dá para
procurar na hora. As atualizações são assinadas e verificadas antes de instalar.

## Requisitos

- Um repositório **git** para analisar.
- Para o terminal com o Claude: [Claude Code](https://docs.claude.com/en/docs/claude-code) instalado.
- Para prender apps externos no Workspace (macOS): permissão de **Acessibilidade**.

## Privacidade

A análise roda inteira na sua máquina e os dados ficam em
`~/Library/Application Support/yagni`. O Yagni não envia telemetria.
