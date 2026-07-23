# 8-Bit Maker — Apha 1.0

Aplicação completa para criação, edição, reprodução e exportação de músicas em estilo 8-bit, distribuída em um único arquivo HTML executável.

## Como executar

1. Renomeie o arquivo `.txt` para `.html`, caso necessário.
2. Abra o arquivo em um navegador moderno.
3. Nenhuma instalação ou servidor local é necessário.

## Principais recursos

* Criação automática de composições 8-bit.
* Tracker e Piano Roll integrados.
* Direção musical e controles de composição.
* Mixer com 12 canais.
* Instrument Designer.
* Macros e parâmetros sonoros.
* Reprodução em tempo real.
* Loop, pausa, reinício e Panic.
* Undo e Redo.
* Salvamento local no navegador.
* Importação e exportação de projetos.
* Exportação em JSON, MIDI e WAV.
* Exportação opcional em MP3 mediante disponibilidade do codificador externo.
* Interface responsiva para desktop, tablet e celular.

## Primeira utilização

O projeto inicial utiliza:

* 12 canais;
* 4 compassos;
* energia Normal;
* loop ativado;
* exportação em 1x.

O Tracker, Piano Roll e outros componentes pesados são construídos somente quando necessários.

## Persistência

Os projetos são armazenados localmente no navegador.

O aplicativo não grava durante a inicialização. O autosave somente é ativado após uma alteração real realizada pelo usuário.

Limpar dados do navegador pode remover os projetos salvos localmente. Recomenda-se exportar projetos importantes em JSON.

## Arquitetura

O aplicativo é totalmente autocontido em um único HTML, com:

* um bloco CSS consolidado;
* um bloco JavaScript consolidado;
* estado musical central compartilhado;
* renderização parcial e lazy;
* atualizações incrementais durante a reprodução;
* separação entre estado, interface, áudio, histórico e persistência;
* uma autoridade oficial por responsabilidade técnica.

## Compatibilidade

Recomenda-se utilizar versões atuais de:

* Google Chrome;
* Microsoft Edge;
* Brave;
* outros navegadores baseados em Chromium.

O funcionamento pode variar em navegadores com suporte incompleto à Web Audio API.

## Arquivos do projeto

* `8-Bit Maker - Apha 1.0.txt` — aplicação completa contendo o HTML.
* `NORMA_PERMANENTE_DE_EVOLUCAO_E_GOVERNANCA_8BIT_MUSIC_MAKER.txt` — regras obrigatórias para futuras evoluções.

## Desenvolvimento futuro

Toda nova versão deve:

* partir da última versão aprovada;
* respeitar a Norma Permanente;
* substituir implementações antigas, sem sobreposição;
* evitar código sem consumidor;
* preservar performance, integridade e compatibilidade;
* passar pela matriz funcional e pela auditoria técnica antes da aprovação.

## Versão

**Produto:** 8-Bit Maker — Apha 1.0
**Formato do projeto:** 12.5
**Schema musical:** 11
**Distribuição:** HTML único e autocontido
