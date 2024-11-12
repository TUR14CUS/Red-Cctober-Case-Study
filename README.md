# Planeamento da Apresentação sobre o Incidente Red October

## Estrutura Geral da Apresentação (4 Elementos)

---

### 1. Introdução às Bases de Cibersegurança (Felix)
- **Objetivo:** Fornecer uma visão geral básica sobre cibersegurança para preparar o terreno antes de entrar no caso específico do **Red October**.
- **Duração:** ~3 minutos

- **Tópicos a Cobrir:**
  - **Definição de Cibersegurança:** O que é cibersegurança e qual a sua importância no contexto atual?
  - **Principais Conceitos de Cibersegurança:**
    - **Confidencialidade, Integridade e Disponibilidade (CID).**
    - **Segurança de Redes, Sistemas e Dados.**
  - **Tipos de Ameaças e Ataques Comuns:** Malware, Phishing, Ransomware, Exploração de Vulnerabilidades, etc.
  - **Eventos e Incidentes de Segurança:**
    - Distinção entre **evento**, **incidente de segurança** e **vulnerabilidade**.

---

### 2. Taxonomia de Incidentes e Ciberameaças (Rodrigo)
- **Objetivo:** Explicar como classificar eventos e incidentes de segurança, preparando para o entendimento do **Red October** dentro desse contexto.
- **Duração:** ~3 minutos

- **Tópicos a Cobrir:**
  - **Taxonomia de Cibersegurança:**
    - O que é taxonomia de cibersegurança e porquê é importante.
    - **Classes de incidentes:** Exemplos de classes de incidentes (ex: Malware, Phishing, Exploração de Vulnerabilidade, Acesso Não Autorizado, etc.).
    - **Tipos de ocorrências:** Incidentes de **sabotagem**, **espionagem**, **fraude**, etc.
  - **O Caso Red October:**
    - Identificar o **Red October** como um ataque direcionado à espionagem.
    - Categorizar o **Red October** dentro da taxonomia**.

---

### 3. O Incidente Red October: Medidas de Contenção, Resolução e Recuperação (Ricardo)
- **Objetivo:** Detalhar como as medidas de contenção, resolução e recuperação poderiam ser implementadas com base nas informações do incidente **Red October**.
- **Duração:** ~5 minutos

- **Tópicos a Cobrir:**
  - **Medidas de Contenção:**
    - O que significa contenção de um incidente de segurança.
    - Medidas sugeridas com base nas características do **Red October**:
      - **Isolamento de redes e sistemas comprometidos.**
      - **Desconexão de máquinas afectadas.**
      - **Alteração de credenciais e bloqueio de acessos comprometidos.**
  - **Medidas de Resolução:**
    - O que é necessário para resolver um incidente de cibersegurança.
    - Ações para erradicar o malware do sistema, como:
      - **Análise e remoção de malware.**
      - **Correção de falhas de segurança (patches, actualizações).**
      - **Auditoria de sistemas comprometidos para detectar outras vulnerabilidades.**
  - **Cuidados em Recuperação:**
    - **Recuperação de sistemas e dados.**
    - **Verificação da integridade dos dados restaurados.**
    - **Monitorização pós-incidente e validação de segurança.**
    - **Melhoria contínua das defesas com base no incidente.**

---

### 4. Lições Aprendidas e Análise de Segurança (Miguel)
- **Objetivo:** Apresentar os **Indicadores de Comprometimento (IOCs)** do incidente e relacioná-los aos princípios de segurança.
- **Duração:** ~4 minutos

- **Tópicos a Cobrir:**
  - **Exemplos de IOCs no Caso Red October:**
    1. **Endereços IP suspeitos**: Identificação de IPs usados para comunicação entre as máquinas infectadas e os servidores de comando e controlo.
    2. **Assinaturas de ficheiros maliciosos (hashes)**: Ficheiros maliciosos usados no ataque, cujos hashes podem ser verificados para identificar a presença do malware.
    3. **Domínios de C&C (comando e controlo)**: Domínios registados pelos atacantes para controlar os sistemas infectados (ex: domínios usados pelo malware para enviar dados roubados).
  - **Princípios Básicos da Segurança de Informação Comprometidos:**
    - Quais princípios de segurança foram violados no **Red October**:
      1. **Confidencialidade:** A espionagem comprometeu a confidencialidade das informações sensíveis.
      2. **Integridade:** Possível alteração de dados para encobrir a actividade maliciosa.
      3. **Disponibilidade:** Embora o principal objectivo do Red October não tenha sido a interrupção de serviços, o ataque pode ter afectado a disponibilidade ao comprometer sistemas e redes.

---

## Conclusão (Rodrigo)
- **Resumo Final:** Reforçar os pontos chave discutidos sobre o **Red October**, destacando como o ataque é um exemplo de espionagem cibernética e as lições que podem ser aprendidas para melhorar a segurança.
- **Conclusão das Medidas e Lições:** Reforçar a importância da **prevenção** e **monitorização contínua** para evitar ataques semelhantes.
