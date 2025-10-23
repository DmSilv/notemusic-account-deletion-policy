# 📱 NoteMusic - Política de Exclusão de Contas

Esta página contém a política de exclusão de contas e dados pessoais do aplicativo **NoteMusic**, conforme exigido pelo Google Play Store.

## 🎯 Objetivo

Esta página é obrigatória para aplicativos que:
- Não permitem criação de conta diretamente no app
- Coletam dados pessoais dos usuários
- Precisam fornecer uma URL pública para solicitação de exclusão

## 📋 Conteúdo da Página

A página inclui todas as informações obrigatórias do Google Play Store:

### ✅ Informações Obrigatórias
- **Nome do app**: NoteMusic
- **Nome do desenvolvedor**: Daniel Silva
- **Etapas detalhadas** para solicitar exclusão da conta
- **Tipos de dados** que são excluídos ou mantidos
- **Período de armazenamento** adicional (7 dias de prazo)
- **Informações de contato** para suporte

### 📊 Dados Cobertos
- Dados pessoais (nome, email, senha)
- Progresso de aprendizado (pontos, níveis, módulos)
- Histórico de quizzes e resultados
- Conquistas e medalhas
- Configurações personalizadas
- Dados do dispositivo

## 🚀 Como Hospedar no GitHub Pages

### 1. Criar Repositório
```bash
# Criar novo repositório no GitHub
# Nome sugerido: notemusic-account-deletion-policy
```

### 2. Configurar GitHub Pages
1. Acesse o repositório no GitHub
2. Vá em **Settings** → **Pages**
3. Em **Source**, selecione **Deploy from a branch**
4. Escolha **main** branch
5. Clique em **Save**

### 3. Upload dos Arquivos
```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/notemusic-account-deletion-policy.git
cd notemusic-account-deletion-policy

# Copie o arquivo HTML
cp account-deletion-policy.html index.html

# Commit e push
git add .
git commit -m "Add account deletion policy page"
git push origin main
```

### 4. URL Final
Após a configuração, a página estará disponível em:
```
https://SEU-USUARIO.github.io/notemusic-account-deletion-policy/
```

## 📱 Como Usar no Google Play Console

1. Acesse o **Google Play Console**
2. Selecione seu app **NoteMusic**
3. Vá em **Política** → **Política do app**
4. Em **URL para exclusão de contas**, cole a URL:
   ```
   https://SEU-USUARIO.github.io/notemusic-account-deletion-policy/
   ```

## 🎨 Características da Página

### ✅ Design Responsivo
- Adaptável para desktop, tablet e mobile
- Cores consistentes com a identidade do NoteMusic
- Gradiente azul/roxo característico

### ✅ Conteúdo Completo
- Instruções passo-a-passo claras
- Informações detalhadas sobre dados
- Múltiplas formas de contato
- Avisos importantes destacados

### ✅ Acessibilidade
- Contraste adequado
- Texto legível
- Navegação intuitiva
- Botão de voltar funcional

## 🔧 Personalização

### Alterar Informações de Contato
Edite o arquivo `account-deletion-policy.html` e modifique:
```html
<a href="mailto:suporte.notemusic@gmail.com" class="email-link">
    suporte.notemusic@gmail.com
</a>
```

### Alterar Período de Retenção
Modifique a seção "Período de Retenção":
```html
<p>Sua conta será <strong>permanentemente excluída após 7 dias</strong>...</p>
```

### Adicionar Logo
Para adicionar um logo real:
```html
<img src="logo-notemusic.png" alt="NoteMusic Logo" class="logo-image">
```

## 📞 Suporte

Para dúvidas sobre esta página ou configuração:
- **Email**: suporte.notemusic@gmail.com
- **Assunto**: GitHub Pages - Política de Exclusão

## 📄 Licença

Esta página é parte do projeto NoteMusic e está sujeita aos mesmos termos de uso do aplicativo.

---

**NoteMusic** - Desenvolvido com ❤️ para o aprendizado musical
