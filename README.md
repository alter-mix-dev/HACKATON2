# HACKATON 2. ASISTENTE COCINERO CON IA. (WhatsApp & Llama-Stack).
* **Arquitectura de Microservicios:** API con **FastAPI** y **Uvicorn** para procesamiento de webhooks asíncronos (`BackgroundTasks`).
* **Orquestación de LLMs:** Integración local de **Llama 3.1 (8B)** mediante **Ollama** y **Llama Stack**.
* **Function Calling:** Motor con **Pandas** sobre más de **173k recetas** para ejecuciones y consultas autónomas por parte del modelo.
* **Control de Flujo:** Manejo de concurrencia con `threading.Lock` por usuario.
* **Control de Seguridad:** Integra filtros automatizados para emergencias o desvío a humanos.
* **Infraestructura:** Entorno automatizado en **Colab** con túneles seguros mediante **Ngrok** y gestión de credenciales con secretos.
