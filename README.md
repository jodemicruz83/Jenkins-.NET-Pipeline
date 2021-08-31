# Jenkins-.NET-Pipeline
Neste projeto utilizamos o win-acme com o pluguin do AWS Route 53 para realizar a validação de dominio e criação de certificados digitais pelos Lets Encrypts.
O Pipeline é dividido em 4 fases 
  Gera o certificado
  Copia para o servidor de destino
  Aplica no Bind do IIS
  Notifica no Google Chat
Apos o Pipeline configuramos uma integração do Jenkins Bot com o Google Chat para notificação Build.
