 EXMDirect — System Analysis

Аналитическая документация к образовательной системе EXMDirect.  
Проект охватывает тестирование, автоматическую проверку, защиту от списывания, идентификацию по QR и взаимодействие с Telegram-ботом.

Структура проекта


exmdirect-system-analysis/
├── README.md
├── CHANGELOG.md
├── LICENSE
├── openapi.yaml
├── docs/
│   ├── EXMDirect_Portfolio.pdf
│   ├── Swagger_Documentation.pdf
│   ├── System_Design.pdf
│   └── entities.md
├── diagrams/
│   ├── bpmn_exam_lifecycle.png
│   ├── er_model_exmdirect.png
│   └── UseCase_Diagram.png
└── .gitignore


Что включено

- "docs/EXMDirect_Portfolio.pdf" — кейс для портфолио с обзором проекта
- "diagrams/" — диаграммы Use Case, BPMN и ER
- "openapi.yaml" — OpenAPI спецификация REST API
- "entities.md" — описание сущностей и связей

 📊 Диаграммы

- Use Case Diagram — роли и действия пользователей
- BPMN Diagram — жизненный цикл экзамена
- ER Diagram — структура данных и их связи

  API

- Спецификация: `openapi.yaml`
- Swagger: `docs/Swagger_Documentation.pdf`

 Технологии (для справки)

- Java 17+, Spring Boot
- PostgreSQL
- JWT-аутентификация
- Telegram Bot API

  Автор

Системный аналитик: Baldruev Sergei  
	Email: baldruev.sergey@email.com  
	Telegram: [@Baldruev_Sergei](https://t.me/Baldruev_Sergei)  
	 LinkedIn: [(9) Sergei Baldruev | LinkedIn](https://linkedin.com)

	Данный проект разработан в рамках перехода от fullstack-разработки к системному анализу. Документация и диаграммы выполнены вручную на основе реальных и моделируемых данных.