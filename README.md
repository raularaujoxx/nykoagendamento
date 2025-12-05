# nykoagendamento
Sistema de agendamentos para barbearia com interface web.
 NykoBarber — Site de Agendamento para Barbearia ✂️💈

 📌 Breve descrição
Um site responsivo para a **Barbearia NykoBarber (Cubatão — SP)** com:
- Lista de serviços
- Galeria de vídeos
- Sistema simples de agendamento client-side (localStorage)
- Notificação via EmailJS

---

🚀  Demo: (https://nykobarberagendamentos.netlify.app/)

---

 🛠️ O que foi desenvolvido:
- Interface responsiva em HTML/CSS (layout escuro): hero, serviços, sobre, galeria e formulário de agendamento.
- Integração com **Flatpickr** (calendário pt-BR), máscara de telefone, seleção de horários em intervalos de 30 minutos e bloqueio de domingos.
- Armazenamento local de agendamentos via localStorage.
- Envio de notificação via "EmailJS" no cliente.

---

 ⚙️ Tech stack
- HTML5, CSS (inline no head), JavaScript (vanilla)
- Bibliotecas: EmailJS (client), Flatpickr (calendário)
- Assets locais: imagens (`imagemlogo.png`, `imageminicio.png...`) e vídeos (`videolucas.mp4`, ...)

---

 📂 Estrutura principal
 - `index.html` — página única (HTML + CSS + JS)
- `assets/` — imagens e vídeos (imagemlogo.png, videolucas.mp4...)
- `README.md` — este arquivo
- `LICENSE` — licença do projeto
- `.gitignore` — arquivos a ignorar
