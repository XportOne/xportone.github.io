# 🧭 **XportOne – Documentação Oficial (F1 Help)**

Bem-vindo ao centro oficial de ajuda do **XportOne**, o plugin desenvolvido para otimizar e automatizar a exportação de pranchas do Revit para **PDF** e **DWG** de forma rápida, consistente e sem erros.

Esta documentação atende ao requisito de **Contextual Help (F1)** da Autodesk App Store.

---

# 📌 **1. Sobre o XportOne**

O **XportOne** é um complemento para Autodesk Revit que simplifica o fluxo de exportação de folhas, permitindo:

- Exportar diversas pranchas simultaneamente  
- Gerar arquivos **PDF** e **DWG** padronizados  
- Definir prefixos, numeração e caminhos de saída  
- Reduzir tempo de trabalho manual  
- Evitar erros comuns de configuração de exportação  

Ele foi projetado para equipes de engenharia e arquitetura que precisam manter produtividade e consistência nos entregáveis.

---

# 🚀 **2. Como usar o XportOne**

### **Passo 1 – Abrir o painel do XportOne**
No Revit, acesse:

> **Add-Ins → Export → Export PDF + DWG**

Clique no botão **Export PDF + DWG**.

---

### **Passo 2 – Selecionar as pranchas**

A interface do XportOne exibirá:

- Lista de pranchas do projeto  
- Caixa de seleção múltipla  
- Filtros (disciplinas, prefixos, padrões de nome)

Selecione as folhas desejadas.

---

### **Passo 3 – Definir opções de exportação**

Você pode configurar:

- Pasta de destino  
- Nome dos arquivos (automático ou personalizado)  
- Exportar **PDF**, **DWG**, ou ambos  
- Criar subpastas automaticamente  
- Aplicar prefixos e sufixos  

---

### **Passo 4 – Exportar**

Clique em **Exportar**.

O XportOne irá gerar os arquivos conforme suas configurações, exibindo mensagens claras sobre:

- Arquivos criados  
- Possíveis erros  
- Caminhos de saída  

---

# ⚙️ **3. Requisitos de Sistema**

- **Autodesk Revit 2025** (ou versão compatível indicada na App Store)  
- .NET 8 Runtime incluído no Revit  
- Permissões de escrita para a pasta de saída  

---

# 📂 **4. Instalação**

O plugin é instalado através de:

### ✔ Autodesk App Store (pacote oficial)  
OU  
### ✔ Instalação manual

Colocando o arquivo **XportOne.addin** e a pasta `.bundle` em:

C:\ProgramData\Autodesk\Revit\Addins\2025\

Após isso, reinicie o Revit.

---

# 🧩 **5. Remoção / Desinstalação**

Para remover:

1. Feche o Revit.  
2. Delete:
   - `C:\ProgramData\Autodesk\Revit\Addins\2025\XportOne.addin`
   - `C:\ProgramData\Autodesk\Revit\Addins\2025\XportOne.bundle\`
3. Abra o Revit novamente.

---

# ❗ **6. Solução de Problemas**

### **O botão do XportOne não aparece**
- Verifique se os arquivos estão no diretório de add-ins.  
- Garanta que o instalador instalou a versão correta (2025).  
- Execute o Revit como administrador.  

---

### **O exportador não abre**
- Pode haver bloqueio do Windows:  
  → Clique direito → *Propriedades* → marque “Desbloquear”.  
- Antivírus pode estar bloqueando `.dll`: adicione exceção.  

---

### **Algumas pranchas não aparecem na lista**
- Verifique se são pranchas válidas (ViewSheet).  
- Folhas dependentes ou templates não são listadas.  

---

### **DWG sai com configuração incorreta**
- Ajuste o template DWG no Revit antes de exportar.  
- As configurações seguem o template ativo do Revit.  

---

### **PDF não é gerado**
- Verifique permissões da pasta de destino.  
- Feche arquivos PDF que já estejam abertos.  

---

# 🔒 **7. Privacidade e Dados**

O XportOne **não coleta, armazena ou transmite** nenhum dado do usuário.

Você pode consultar a política completa em:

👉 **https://xportone.github.io/**

---

# 📘 **8. Licenciamento**

O XportOne é distribuído através da Autodesk App Store sob a licença de uso da plataforma.

---

# 🆘 **9. Suporte Técnico**

Se você encontrou algum problema, precisa de ajuda ou quer sugerir melhorias:

### 📧 **E-mail de suporte**
**xportone.plugin@gmail.com**

### 🛠 Tempo de resposta típico
Dentro de **24 a 48 horas úteis**.

---

# 🎉 **Obrigado por usar o XportOne!**

Este plugin foi desenvolvido para tornar a exportação do Revit mais rápida, simples e confiável.  
Agradecemos por utilizar nossa solução.
