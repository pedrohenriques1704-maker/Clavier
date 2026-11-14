# Clavier

## Versão 6.0.0 — pacote consolidado (pré-publicação)

- Todas as correções anteriores de mídia WAV, teste de áudio e atualização do cache.
- Calendário adaptativo de 15 sessões, preservação de histórico e tempo total.
- Oficina de piano: caderno de obras por compassos, com prioridades inseridas quando a obra aparece no plano; biblioteca de 48 combinações de tonalidade e modo; desafios de escala com teclado virtual e MIDI; leitura de quatro compassos, em clave de Sol ou Fá; gravação local para escuta e exportação; metas, XP e tempo cronometrado.
- Treinamento rítmico com sinais visuais de preparação, escuta e reprodução.
- Relatório manual para o ChatGPT inclui caderno, leitura de frases, escalas e tempo medido. Nenhuma API paga.

## Antes de publicar

Esta branch `release/clavier-6` é de preparação. Não mesclar na `main` até a confirmação de saldo e autorização do usuário. Não abrir PR até essa autorização, para evitar previews desnecessários. Verificar que branch deploys e previews do Netlify não estão habilitados, caso haja consumo adicional. A versão efetivamente publicada no Netlify deve ser verificada após a mesclagem.

No iPhone: exportar backup, abrir pelo Safari, verificar rodapé 6.0.0, testar áudio de três notas, ouvir um intervalo, iniciar exercício rítmico, verificar gravação e instalação. Manter o mesmo domínio e não limpar armazenamento local. Testes de lógica em ambiente simulado não garantem reprodução ou MIDI físico. MIDI depende do navegador e dispositivo; gravações não persistem após fechamento, devem ser salvas. Sem sincronização automática ou análise de áudio por IA.
