# 💰 Controle de Consórcio Familiar 2026

Um dashboard moderno e responsivo para gerenciar pagamentos de consórcio familiar com suporte mobile-first.

## ✨ Funcionalidades

- 📱 **Mobile First**: Totalmente responsivo com cards expansíveis para celular
- 📊 **Tabela Interativa**: Coluna de nome fixa (sticky) para melhor navegação
- 🔄 **Ordenação Automática**: Lista organizada pelo mês de recebimento de cada pessoa
- 🎯 **Destaque Visual**: Mês de recebimento destacado em dourado em cada linha
- 💳 **Dados de PIX**: Exibe chave PIX e valor para transferência
- 🔍 **Filtro de Busca**: Busque rápido por nome
- 📅 **Status de Pagamento**: Visual com ✓ (pago) e ✗ (não pago) em cada mês
- ⏳ **Loading State**: Indicador de carregamento enquanto lê o CSV
- 🎨 **Design Moderno**: Tailwind CSS com gradientes e animações

## 📁 Arquivos

- `index.html` - Arquivo HTML único com todo o código (HTML, CSS e JavaScript)
- `dados.csv` - Planilha de dados com informações das pessoas e pagamentos
- `README.md` - Este arquivo

## 🚀 Como Usar

### Online (Recomendado)
1. Acesse a versão hospedada (após fazer upload no GitHub Pages)
2. Abra em qualquer navegador
3. Use filtro para buscar por nome
4. Veja o status de pagamentos de cada mês

### Local
1. Baixe os arquivos (`index.html` e `dados.csv`)
2. Coloque na mesma pasta
3. Abra `index.html` no navegador
4. Pronto! Tudo funciona offline

## 📋 Estrutura do CSV

O arquivo `dados.csv` deve ter as seguintes colunas:

```
Nome;Mes_Recebimento;PIX;Valor;Janeiro;Fevereiro;Março;Abril;Maio;Junho;Julho;Agosto;Setembro;Outubro;Novembro;Dezembro
```

**Colunas:**
- `Nome` - Nome da pessoa
- `Mes_Recebimento` - Mês que ela recebe (1-12)
- `PIX` - Chave PIX para transferência
- `Valor` - Valor em reais
- `Janeiro` a `Dezembro` - Status de pagamento (V = pago, X = não pago)

**Exemplo:**
```
David;3;123.456.789-00;1500.00;V;X;X;X;X;X;X;X;X;X;X;X
```

## 🛠️ Tecnologias

- **HTML5** - Estrutura semântica
- **Tailwind CSS** - Styling responsivo
- **JavaScript Vanilla** - Sem dependências externas
- **PapaParse** - Parse de CSV
- **SVG Icons** - Ícones nativos

## 📱 Responsividade

- **Desktop**: Tabela completa com coluna sticky
- **Tablet**: Tabela otimizada
- **Mobile**: Cards expansíveis com toggle de vista

## 🌐 Deploy no GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Vá em **Settings → Pages**
4. Selecione **Deploy from a branch** → **main**
5. A URL será: `https://seu-usuario.github.io/consorcio-familia/`

## 📝 Editar Dados

Abra `dados.csv` em qualquer editor de texto (Excel, Planilha Google, VS Code) e:
1. Adicione/remova pessoas
2. Atualize pagamentos (V ou X)
3. Salve o arquivo
4. Recarregue a página (Ctrl+F5) para ver as mudanças

## ⚙️ Cache

Se os dados não atualizarem:
1. Pressione **Ctrl+Shift+Delete** para limpar cache
2. Recarregue a página

## 📧 Suporte

Dúvidas? Abra uma issue no repositório ou contacte o desenvolvedor.

---

**Desenvolvido com ❤️ para a Família**
