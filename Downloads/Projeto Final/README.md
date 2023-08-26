# Sprint-08

# PLANEJAMENTO DE TESTE DA API http://localhost:3000 💻

### 1- Objetivo do teste: 

Análisar e Observar se tem algum __Bug/Error__.

Análisar se está tudo certo com as rotas de __Cinema API__

### 2- Estratégia de teste:

__Testes manuais:__ testes exploratórios seguindo casos de teste predefinidos.

__Testes automatizados:__ fazer testes automatizados para garantir a regressão

__Testes de Performance:__

### 3- Users Stories:


### 4- Cobertura de teste


### 5- Mapa Mental Ultilizado 🗺️💡
 
![Cinema_API](/uploads/b10451374db9bef6d5106b28322e7755/Cinema_API.png)
 
### 6- Casos de teste:

### Testes Manuais:

### Teste de Performance:

### 1. Teste de Carga Média (Load testing)

- Objetivo: Avaliar o desempenho da aplicação sob uma carga média.
- Configuração:
  - Aumentar gradualmente de 1 para 50 usuários em 1 minuto.
  - Manter 50 usuários por 1 minuto.
  - Reduzir para 0 usuários em 10 segundos.
- Critérios de Avaliação:
  - Erros de solicitação HTTP devem ser inferiores a 1%.
  - 95% das solicitações devem ter uma duração abaixo de 200ms.

### 2. Teste Rápido (Smoke Test)
- Objetivo: Verificar rapidamente a funcionalidade básica com um número baixo de usuários virtuais.
- Configuração:
  - Utilizar 20 usuários virtuais (VUs).
  - Duração de 1 minuto.
- Critérios de Avaliação: (Mesmos do Teste de Carga Média)

### 3. Teste de Longa Duração (Soak Test)
- Objetivo: Avaliar a estabilidade e o desempenho da aplicação sob carga contínua.
- Configuração:
  - Aumentar gradualmente de 1 para 30 usuários em 10 segundos.
  - Manter 30 usuários por 10 segundos.
  - Reduzir para 0 usuários em 15 segundos.
- Critérios de Avaliação:
  - Erros de solicitação HTTP devem ser inferiores a 1%.
  - 95% das solicitações devem ter uma duração abaixo de 200ms.

### 4. Teste de Pico (Spike Test)
- Objetivo: Avaliar a resposta da aplicação a picos repentinos de tráfego.
- Configuração:
  - Aumentar rapidamente para 30 usuários em 50 segundos.
  - Reduzir rapidamente para 0 usuários em 30 segundos.
- Critérios de Avaliação:
  - Erros de solicitação HTTP devem ser inferiores a 1%.
  - 95% das solicitações devem ter uma duração abaixo de 200ms.

### 5. Teste de Estresse (Stress Test)
- Objetivo: Determinar a capacidade máxima da aplicação e identificar pontos de falha.
- Configuração:
  - Aumentar gradualmente de 1 para 50 usuários em 30 segundos.
  - Manter 50 usuários por 20 segundos.
  - Reduzir para 0 usuários em 15 segundos.
- Critérios de Avaliação:
  - Erros de solicitação HTTP devem ser inferiores a 1%.
  - 95% das solicitações devem ter uma duração abaixo de 200ms.

### 7- Ambiente de teste:

*  Postman
*  K6


| Sistema Operacional |
|---|
| Windows |

### 8- Cronograma :

| Data | Atividades |
|---|---|
| 25/07/23 - Dia 1 | AWS Partner Accreditation (Cloud Economics) |
| 26/07/23 - Dia 2 | AWS Partner Accreditation (Cloud Economics) |
| 27/08/23 - Dia 3 | Primeiros passos com K6 |
| 28/08/23 - Dia 4 | Entendendo resultados e métricas|
| 29/07/23 - Dia 5 | Entendendo resultados e métricas |
| 30/07/23 - Dia 6 | Evolução Challenge,Exercícios challenge |
| 31/07/23 - Dia 7 | Evolução Challenge |
| 01/08/23 - Dia 8 | Mentoria & Exercícios Challenge|
| 02/08/23 - Dia 9 | Evolução Challenge| 
| 03/08/23 - Dia 10 | Apresentação Challenge |


### 9- Referências :

Olhei o Respositórios de [Cristiane](https://gitlab.com/Cristiane777/sprint-1-processos-ageis-e-fundamentos-de-teste/-/blob/pb_sprint3/README.md?plain=1) como base para minha organização da estrutura do documento.


