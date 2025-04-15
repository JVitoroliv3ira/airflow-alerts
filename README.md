# airflow-alerts

> Notificações inteligentes e customizáveis para Apache Airflow, com suporte a múltiplos canais e integração simples via decorators.

---

## ✨ Visão geral

**airflow-alerts** é uma biblioteca para facilitar o envio de alertas em pipelines do Apache Airflow. Com uma configuração simples e intuitiva, você pode notificar falhas, sucessos ou eventos personalizados diretamente do seu DAG ou task.

---

## 🔧 Funcionalidades

- 📣 Notificações automáticas de falhas, sucessos e eventos customizados  
- 📬 Integração com **Email** e **Discord**  
- 🧩 Decorators para DAGs e tasks — sem precisar escrever callbacks manualmente  
- 📨 Sistema de templates customizáveis (usando Jinja2)  
- 🛠️ Configuração global e por DAG/task  
- 🔄 Suporte a múltiplos canais simultâneos  
- 🔕 Silent mode para evitar flood de notificações  

---

## 💡 Motivação

O Airflow possui suporte a callbacks, mas a configuração de notificações ainda é repetitiva e limitada. Com **airflow-alerts**, a ideia é transformar notificações em algo fácil de aplicar, com uma abordagem elegante e extensível — sem abrir mão da flexibilidade.

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues, enviar PRs ou sugerir novos canais de notificação.

---

## 🧾 Licença

Este projeto está licenciado sob a **GPL v3**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
