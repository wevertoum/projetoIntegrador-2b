## **📍 1. Tela de Login**
🔹 **Descrição:** Tela inicial para autenticação do usuário.  
🔹 **Seções:**  
- Campo de e-mail  
- Campo de senha  
- Botão "Entrar"  
- Link "Esqueci minha senha"  

---

## **📍 2. Dashboard do Organizador**  
🔹 **Descrição:** Página principal do organizador, mostrando listagem geral dos eventos.  
🔹 **Seções:**  
- Listagem dos eventos cadastrados  
- Botão "Criar Novo Evento"  
- Card de resumo do evento (data, vagas, ocupação, status)  

---

## **📍 3. Cadastro de Evento**  
🔹 **Descrição:** Formulário para o organizador cadastrar um evento.  
🔹 **Seções:**  
- Nome do evento  
- Data e horário  
- Número de vagas  
- Valor da inscrição  
- Configuração de quartos (adicionar quartos e definir gênero)  
- Botão "Salvar"   

---

## **📍 4. Tela de Inscrição do Acampante**  
🔹 **Descrição:** Página onde o acampante escolhe um evento e se inscreve.  
🔹 **Seções:**  
- Informações do evento (nome, data, vagas, valor)  
- Botão "Inscreva-se"  
- Escolha do quarto e leito  
- Seleção da forma de pagamento  
- Botão "Confirmar Inscrição"  

🔹 **Fluxo:**  
✅ Se houver leitos disponíveis → Confirma inscrição e redireciona para a tela de confirmação.  
❌ Se não houver → Exibe mensagem "Evento lotado".  

---

## **📍 5. Seleção de Quartos e Leitos**  
🔹 **Descrição:** Tela onde o acampante visualiza os quartos disponíveis e escolhe um leito.  
🔹 **Seções:**  
- Lista de quartos disponíveis  
- Exibição dos leitos ocupados/livres  
- Nome dos ocupantes já cadastrados  
- Botão "Selecionar Leito"  

🔹 **Regras:**  
- O usuário só pode ver quartos do mesmo gênero.  
- Atualização em tempo real ao selecionar um leito.  

---

## **📍 6. Tela de Confirmação de Inscrição**  
🔹 **Descrição:** Página confirmando a inscrição no evento.  
🔹 **Seções:**  
- Mensagem de sucesso "Inscrição confirmada!"  
- Detalhes da inscrição (evento, quarto, leito)  
- Instruções para pagamento e participação  

🔹 **Ações:**  
- Botão "Baixar Comprovante"  
- Botão "Voltar para Eventos"  

---

## **📍 7. Tela de Supervisão do Evento**  
🔹 **Descrição:** Página onde o supervisor acompanha o evento.  
🔹 **Seções:**  
- Lista de inscritos  
- Visualização dos quartos e ocupação  
- Botão "Exportar Lista (CSV)"  
- Botão "Enviar Lembrete para Todos"  

---

## **📍 8. Tela de Edição de Evento**  
🔹 **Descrição:** Página para editar as informações de um evento existente.  
🔹 **Seções:**  
- Formulário com os dados do evento já preenchidos  
- Opção de editar quartos e vagas  
- Botão "Salvar Alterações"  

🔹 **Fluxo:**  
- Se alterar número de vagas, recalcular disponibilidade de inscrições.  
- Se um quarto já estiver ocupado, bloquear remoção desse quarto.  

---

## **📍 9. Tela de Envio de Lembretes Automáticos**  
🔹 **Descrição:** Tela onde o organizador programa os lembretes para os acampantes.  
🔹 **Seções:**  
- Lista de inscritos  
- Opção de programar envio para todos  
- Visualização do status de envio  

🔹 **Fluxo:**  
✅ Envio bem-sucedido → Exibe "Lembrete enviado com sucesso".  
❌ Falha no envio → Exibe "Erro ao enviar lembrete".  