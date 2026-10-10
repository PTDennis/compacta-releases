# Compacta — versões

Instaladores da **Compacta**, app para macOS (Apple Silicon e Intel, macOS 14 ou posterior) para criar, explorar e extrair arquivos ZIP, 7z, RAR, TAR e outros.

## Instalar

1. Descarregue o `Compacta-x.y.dmg` da [versão mais recente](../../releases/latest).
2. Abra o DMG e arraste a Compacta para **Aplicações**.
3. Na primeira abertura o macOS mostra um aviso (a app não está notarizada pela Apple): vá a **Definições do Sistema → Privacidade e Segurança** e carregue em **Abrir mesmo assim**.

Depois disso, a Compacta atualiza-se sozinha: quando houver uma versão nova, propõe a atualização e reabre-se (Definições → Atualizações da Compacta).

## Segurança das atualizações

Cada versão inclui `Compacta-x.y.zip` e uma assinatura `Compacta-x.y.zip.sig` (Ed25519). A app só instala pacotes cuja assinatura corresponde à chave pública que traz consigo.

## Componentes de terceiros

Inclui o 7-Zip (`7zz`) de Igor Pavlov, licença GNU LGPL (com a restrição unRAR para a descompressão RAR) — código-fonte em https://www.7-zip.org. O texto das licenças está dentro da app (menu Ajuda → Licenças de terceiros).
