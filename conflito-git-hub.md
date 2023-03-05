Se o usuário gerou um conjunto de chaves públicas/privadas ssh antes

verifique qual chave foi autorizada nas configurações da sua conta github ou gitlab
determine qual chave privada correspondente deve ser associada do seu computador local
eval $(ssh-agent -s)

definir onde as chaves estão localizadas
ssh-add ~/.ssh/id_rsa
