# Especificação de Requisitos do Sistema (ERS/SRS)

## Descrição Geral do Sistema
O sistema Spotify é um app de Streaming de Músicas.  
Ver como um sistema entrega estabilidade ao reproduzir músicas de forma direta e sem interrupções em servidores dedicados.

---

## Requisitos Gerais

### Requisitos Funcionais (RF)
| ID | Descrição | Prioridade |
|----|------------|-----------|
| RF01 | O sistema deve permitir que o usuário crie uma conta utilizando e-mail, senha ou login por redes sociais.|Essencial|
| RF02 | O sistema deve permitir que o usuário busque músicas, artistas, álbuns e playlists.|Essencial |
| RF03 | O sistema deve permitir a criação e edição de playlists personalizadas. | Importante |
| RF04 | O sistema deve permitir que o usuário baixe músicas para ouvir offline (função premium).|Desejável |
| RF05 | O sistema deve permitir que o usuário reproduza músicas, com opções de pausar, avançar e retroceder faixas. | Essencial |

### Requisitos Não Funcionais (RNF)
| ID | Descrição | Prioridade |
|----|------------|-----------|
| RNF01 | O sistema deve responder em até 2 segundos por requisição. | Essencial |
| RNF02 | O acesso deve ser protegido por autenticação segura. | Essencial |
| RNF03 | A interface deve ser intuitiva e responsiva. | Essencial |

### Regras de Negócio (RN)
| ID | Descrição | Prioridade |
|----|------------| -----------|
| RN01 | Cada usuário deve possuir um e-mail único para cadastro. | Essencial |
| RN02 | Uma tarefa concluída não pode ser editada. | Essencial | Essencial |

---

## Diagramas UML

### Diagrama de Casos de Uso
![Diagrama de Casos de Uso](docs/casos_de_uso.jpg)

### Diagrama de Sequência
![Diagrama de Sequência](docs/diagrama_sequencia.png)

### Diagrama de Atividades
![Diagrama de Atividades](docs/diagrama_atividades.png)

---

## Arquitetura do Sistema
O sistema adota o estilo arquitetural **MVC (Model–View–Controller)**, separando responsabilidades entre:
- **Model:** lógica e acesso a dados.  
- **View:** interface e interação com o usuário.  
- **Controller:** coordenação entre as camadas.

- ![Arquiteura do Sistema](docs/arquiterura.png)
