# Sistema de Atención al Cliente Automático (n8n + IA + RAG + HITL)

Repositorio oficial del trabajo final. Sistema de atención al cliente automatizado con enrutamiento inteligente, arquitectura RAG, aprobación humana vía Gmail interactivo y optimización avanzada de costos.

---

## 📄 Documentación Principal

Toda la especificación técnica, manual operativo de datos, esquemas de transferencia JSON, arquitectura y matriz de costos se encuentran consolidados en la documentación oficial:

* 📥 **[Ver / Descargar Entrega Final (PDF)](./Entrega%20Final.pdf)**

---

## 🛠️ Stack Tecnológico

* **Orquestador:** n8n
* **Modelo Principal:** Google Gemini 3.1 Flash Lite (Temperatura 0.0)
* **Modelo Respaldo (Fallback):** Claude Haiku
* **Base de Conocimiento (RAG):** Gemini Embeddings 2 + Notion API
* **Canales & Supervisión:** Gmail (`sendAndWait` - HITL) y Slack API

---

## 💰 Resumen económico

* **Costo Operativo Final:** **~$0.21 USD** por cada 1,000 consultas.
* **Estrategia de Optimización:** Implementación de *Prompt Caching* (75% de descuento en el System Prompt fijo) y selección de modelos ultralivianos.
* **Procesamiento:** Ejecución en tiempo real (Sincrónico) para garantizar respuesta inmediata y experiencia de usuario.
