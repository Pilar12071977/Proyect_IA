** Creación y Fine-Tunnig de un Chatbot para un bar **
(No he podido terminar la ejecución por falta de RAM)
Pasos:
- Creación de un Dataset con preguntas y sus respectivas respuestas sobre el bar.
- Guardar el Dataset como un CSV
- Tokenizar el Dataset, para ello utilizó datasets de Hugging Face para convertir el dataset en un formato compatible y proceder con la tokenización de las preguntas y respuestas.
- Entrenamiento del Modelo (Fine-Tuning), defino los parámetros de entrenamiento, creo el modelo y realizo el ajuste fino con el dataset de preguntas y respuestas
- Configurar el Pipeline de RAG(Retriever-Augmented Generation), configuró un pipeline para integrar capacidades de recupreación de iinformación utilizando el modelo facebook/rag-token-base.
- Generación de respuestas, el sistema de preguntas y respuestas se implementó con un "promt engineering", que genera respuestas a partir de las preguntas del usuario y el contexto recuperado.
- Prueba del Sitema (por realizar)
