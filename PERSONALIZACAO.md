# 📝 Guia de Personalização do Portfolio

Este arquivo contém todas as instruções para personalizar seu portfolio com suas informações pessoais.

## 🎯 Passos para Personalização

### 1. Informações Básicas (index.html)

#### Nome e Título
- **Linha 6**: Altere o título da página
  ```html
  <title>Seu Nome - Sua Profissão</title>
  ```

- **Linha 15**: Altere o nome no logo da navegação
  ```html
  <a href="#home">Seu Nome</a>
  ```

#### Seção Hero (Apresentação)
- **Linha 32**: Altere seu nome completo
  ```html
  <h1 class="hero-title">
      Olá, eu sou [Seu Nome Completo]
  </h1>
  ```

- **Linha 35**: Descreva sua especialização
  ```html
  <p class="hero-subtitle">
      [Sua especialização e área de atuação]. Descreva brevemente sua experiência e foco profissional.
  </p>
  ```

### 2. Projetos

Para cada projeto (4 projetos incluídos), altere:

#### Projeto 1-4 (aproximadamente linhas 55-150)
- **Título**: `<h3 class="project-title">Nome do Projeto X</h3>`
- **Descrição**: Conte sobre o projeto, desafios e tecnologias
- **Tags**: `<span class="tag">Sua Tecnologia</span>`

### 3. Experiência Profissional

#### Timeline de Carreira (aproximadamente linhas 155-200)
Para cada experiência:
- **Data**: `<div class="timeline-date">Ano - Ano</div>`
- **Cargo**: `<h3 class="timeline-title">Seu Cargo</h3>`
- **Empresa**: `<h4 class="timeline-company">Nome da Empresa</h4>`
- **Descrição**: Conte suas responsabilidades e conquistas

### 4. Habilidades

#### Habilidades Técnicas (aproximadamente linha 205)
Substitua as tecnologias pelos seus conhecimentos:
```html
<span class="skill-tag">Sua Tecnologia</span>
```

#### Habilidades Comportamentais (aproximadamente linha 220)
Adicione suas soft skills:
```html
<span class="skill-tag">Sua Habilidade</span>
```

### 5. Informações de Contato (aproximadamente linha 240)

- **WhatsApp**: `href="https://wa.me/5511999999999"`
- **Email**: `href="mailto:seu.email@exemplo.com"`
- **LinkedIn**: `href="https://www.linkedin.com/in/seu-perfil"`
- **Telefone**: `href="tel:+5511999999999"`

### 6. Footer (linha 260)
```html
<p>&copy; 2025 [Seu Nome] - [Sua Profissão]. Todos os direitos reservados.</p>
```

## 🎨 Personalização de Cores

No arquivo `css/style.css`, você pode alterar o esquema de cores modificando as seguintes variáveis:

- **Cor principal**: Procure por `#60a5fa` (azul atual)
- **Cor secundária**: Procure por `#3b82f6` (azul mais escuro)
- **Fundo escuro**: `#0f172a` e `#1e293b`

## 📸 Adicionando Imagens

### Foto de Perfil
1. Adicione sua foto na pasta do projeto
2. Substitua o placeholder na linha 50:
   ```html
   <!-- Remova esta div -->
   <div class="profile-placeholder">
       <i class="fas fa-user"></i>
   </div>
   
   <!-- Adicione isto -->
   <img src="sua-foto.jpg" alt="Seu Nome" class="profile-image">
   ```

3. Adicione este CSS:
   ```css
   .profile-image {
       width: 300px;
       height: 300px;
       border-radius: 50%;
       object-fit: cover;
       border: 4px solid rgba(255, 255, 255, 0.2);
   }
   ```

### Imagens dos Projetos
1. Adicione screenshots dos seus projetos
2. Substitua os placeholders:
   ```html
   <!-- Remova isto -->
   <div class="project-placeholder">
       <i class="fas fa-fire-extinguisher"></i>
   </div>
   
   <!-- Adicione isto -->
   <img src="projeto1.jpg" alt="Nome do Projeto 1">
   ```

## 🚀 Próximos Passos

1. **Teste**: Abra o index.html no navegador para ver suas alterações
2. **Responsividade**: Teste em diferentes tamanhos de tela
3. **SEO**: Adicione meta tags no `<head>`
4. **Performance**: Otimize imagens antes de usar
5. **Deploy**: Suba para GitHub Pages, Netlify ou Vercel

## 📞 Dicas Finais

- Mantenha as descrições concisas mas informativas
- Use verbos de ação nas descrições de experiência
- Inclua palavras-chave relevantes para sua área
- Teste todos os links antes de publicar
- Considere adicionar um blog ou seção de artigos

Boa sorte com seu novo portfolio! 🌟
