# PROJETO-RAIZ
 
Projeto baseado em API de mangás

# Códigos de status HTTP

Na maioria dos casos, as APIs do Bug Livre responderão às solicitações com as definições de código de status HTTP padrão. Se a API não conseguir validar uma solicitação, ela responderá com uma mensagem de erro de validação (JSON ou XML) descrevendo o problema.

Aqui estão alguns códigos de status HTTP comuns que você pode encontrar:


200 => OK

201 => CREATED

202 => ACCEPTED (Indica que a solicitação foi recebida, mas ainda não foi concluída.)

204 => NO CONTENT (Requisição sem resposta.)

301 => MOVED PERMANENTLY(A URL do recurso solicitado foi alterada permanentemente.)

302 => FOUND (Redirecionamento temporário.)


400 => BAD REQUEST (A solicitação não pôde ser compreendida pelo servidor devido à sintaxe incorreta.)

401 => UNAUTHORIZED (Usuário não logado.)

402 => FORBIDDEN (Usuário logado mais proibido de acessar esse recurso.)

404 => Not Found (Página não encontrada.)

405 => METHOD NOT ALLOWED (O método HTTP de solicitação é conhecido pelo servidor, mas foi desativado e não pode ser usado para esse recurso.)


500 => Erro interno do servidor (O servidor encontrou uma condição inesperada que o impediu de atender à solicitação.)

501 => NOT IMPLEMENTED (O método HTTP não é suportado pelo servidor e não pode ser manipulado.)

502 => BAD GATEWAY (O servidor obteve uma resposta inválida enquanto trabalhava como gateway para obter a resposta necessária para lidar com a solicitação.)

503 => SERVICE UNAVAILABLE (O servidor não está pronto para lidar com a solicitação.)