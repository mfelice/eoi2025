# Herramientas de inteligencia artificial para la práctica y evaluación de idiomas

## Introdución

https://teachablemachine.withgoogle.com/train

## Modelos de lenguaje

### Tarea
**Crear un ejercicio _cloze_ a partir del siguiente texto. Usar un modelo de lenguaje para identificar palabras óptimas para eliminar.**

Francisco era un niño apasionado por el ajedrez desde pequeño. Un día, mientras jugaba en la plaza, conoció a un gran maestro que lo vio jugar y decidió tomarlo bajo su cuidado. Con sus enseñanzas, Francisco rápidamente mejoró sus habilidades y pronto se convirtió en un famoso jugador de ajedrez. A medida que crecía, Francisco ganó varios torneos importantes y se estableció como uno de los mejores jugadores de España. Su talento natural y dedicación al juego hicieron que fuera considerado uno de los grandes maestros de ajedrez de todos los tiempos.

### BERT
Español:  
https://huggingface.co/spaces/CeibalUY/enmascaramiento_lenguaje  
https://huggingface.co/spaces/mrolando/mask_lenguage_spanish  
https://huggingface.co/spaces/srjosueaaron/fill-mask-demo  

Inglés:  
https://huggingface.co/spaces/UserConfused/bert-base-uncased  
https://huggingface.co/spaces/pulkitmehtawork/modern_bert_large_fill_mask  
https://huggingface.co/spaces/ysdede/fill-mask-demo  
https://huggingface.co/spaces/merve/fill-in-the-blank  
https://huggingface.co/spaces/eriksarriegui/word_probs  

### Predictores de palabras basados en n-gramas (inglés) 
https://fschoen.shinyapps.io/NextWordPrediction/  
https://philferriere.shinyapps.io/WordPredictR/  
https://technicalelvis.shinyapps.io/shiny_demo_word_predictor/  

## Corrección gramatical

### Tarea

**Corregir el siguiente texto:**

Queria presentar me, me llamo Olga, vivo en Rusia, en el pais, que nunca no haya el sol, en Moscu, el la cuidad, en la que nadie no sonria.
Termine el universidad de Moscu, la facultad fisica. Tengo un trabajo en la empresa petrolera como engeniero.
Tengo una hija violinista y dos hijos, el mayor es ingeniero, y menor es el gionista.
Hace sinco años yo y mi marido hemos comprado el piso en Tenerife, una de Islas Canarias. Este es lo que he motivado mi solicitud de estudiar espanol.
Aparte de esto me gustan mucho cultura, literatura, pintura y escultura de España y historia de España y America Latina. Me parece que las peliculas españolas son unos de mas interesantes en el mundo.

### Correctores gramaticales
Español:  
https://spanishchecker.com/es/  
https://abccorrector.com/corrector-castellano.html  
https://lorcaeditor.com/  

Inglés:  
**Grammarly:** https://www.grammarly.com/grammar-check  
**Ginger:** https://www.gingersoftware.com/grammarcheck  

Multilingües:  
**LanguageTool:** https://languagetool.org/  
**QuillBot:** https://quillbot.com/grammar-check  
**Reverso:** https://www.reverso.net/ortografia/  
**Zoho:** https://www.zoho.com/es-xl/writer/free-grammar-checker.html  

### ERRANT
https://nlptoolbox.cl.cam.ac.uk/errant/ ([ejemplo](https://nlptoolbox.cl.cam.ac.uk/errant/?206b6d2de6b44c54a3c52f0d6581686b))  

## Evaluación automática de textos

### Tarea  

**Determinar manualmente el nivel MCER del siguiente texto:**  
  
I think that study abroad is a beautiful experience for some students. They learn a new langage, meet new people and discover a new culture. But for others, being far from what they know, from their friends and family, could be catastrophic. For example, there are host families who are totally unfriendly with foreigner students. In this case, the student coul feel very bad, sad and maybe he will isolate him/herself from the social world. Furthemore, some students could be 'alone' and lost when they go abroad to study. It could lead to school/academic failure and to depression.
So I don't think that study abroad should be a compulsory part of education. It depends too much on the student's personality and the situation within he/she will be.

### Otros sistemas  
https://www.paperrater.com/free_paper_grader (basado en features)  
https://huggingface.co/spaces/KevSun/MultiDim_Automated_Scoring_English_Essays (basado en deep learning)  

### Write&Improve (inglés)
https://writeandimprove.com/workbooks#/wi-workbooks  

### Simuladores de evaluación para IELTS  
https://www.writinglab.io/ielts-essay-checker  
https://engnovate.com/ielts-writing-task-2-essay-checker/  
https://upscore.ai/trainer  

## Reconocimiento de voz
**Tarea**
1. Escuchar el siguiente fragmento de audio y transcribir lo que se dice.
2. Usar un servicio de reconocimiento de voz para generar una transcripción del audio. 
3. Comparar ambas transcripciones y calcular la tasa de error (WER).

https://github.com/user-attachments/assets/8ecd2eec-a426-4020-8eea-dad5ff3fcfe2

Fuente: https://www.youtube.com/watch?v=UKKIkPda4GY

### Servicios de reconocimiento de voz  
**OpenAI Whisper:** https://huggingface.co/spaces/openai/whisper | https://course-demos-whisper-small.hf.space/  
**AssemblyAI:** https://www.assemblyai.com/playground/source  
**TalkNotes:** https://talknotes.io/tools/transcribe-to-text  
**Aspose:** https://products.aspose.ai/total/speech-to-text/  
**Speech-to-text:** https://www.speech-to-text.cloud/

**Comparación de ASR:** https://demos.speechmatics.com/

### Calculadora WER
https://www.amberscript.com/en/wer-tool/

## Síntesis de habla (texto a voz)
### Tarea
Crear una tarea de compresión auditiva basada en un diálogo entre tres personas con distintos acentos.

1. Crear un breve diálogo y una pregunta de comprensión opción múltiple.
2. Crear un fichero de audio para cada intervención mediante el uso de un servicio de texto a voz.
3. Unir todos los ficheros de audio individuales en un único fichero.

**Diálogo de ejemplo**  
Ana es de España, Bruno es de Argentina y Carlos es de Colombia.

**1-A:** Hola chicos, ¿cómo están?  
**2-B:** Hola Ana, nada mal, gracias.  
**3-C:** Sí, todo bien. ¿Y tú?  
**4-A:** Para ser honesta, un poco nerviosa... Hoy tengo mi examen de manejo.  
**5-B:** ¿En serio? ¡Pensé que era la próxima semana!  
**6-A:** Originalmente sí, pero me lo cambiaron.  
**7-C:** Qué mala suerte. Pero has practicado mucho, ¡seguro que aprobarás!  
**8-A:** ¡Eso espero!

**Pregunta**  
Ana va a rendir su examen de manejo. ¿Por qué está nerviosa?

a) No ha practicado lo suficiente.  
b) Su examen fue postergado para la semana que viene.  
c) Su examen es hoy.  
d) No se siente confiada de aprobar.  

### Servicios de texto a voz
https://ttsfree.com/  
https://ttsmp3.com/  
https://ttstool.com/   
https://speechgen.io/  
https://www.audyo.ai/  
https://luvvoice.com/  
https://speechgen.io/  
https://freereadtext.com/en  
https://crikk.com/text-to-speech/  
https://texttospeech.online/  

### Unificador de audio
https://audio-joiner.com/

## IA generativa

### LLMs
**ChatGPT:** https://chat.openai.com/  
**Gemini:** https://gemini.google.com/  
**Bing Chat (GPT-4):** https://www.microsoft.com/en-us/edge/launch/bing-chat-features?form=MT00IR  
**ChatGPT (no oficial):** https://chat.chatgptdemo.net/ | https://talkai.info/chat/  
**Perplexity:** https://labs.perplexity.ai/  
**Llama 2:** https://www.llama2.space/  
**Claude:** https://claude.ai/  

**Directorio de prompts:** https://prompts.chat/  

### Tarea
Analizar los dos textos y decidir si fueron generados por IA o un humano.  

**Texto 1**  
Every country in the world suffers environmental catastrophes. This is a natural consequence of the struggle between development and environment. If a country decided to live isolated from the rest of the world, living on what it can naturally grow and produce, it surely wouldn’t be highly polluted. But we all want exotic food and technological items from all over the world, so we have to pay the price. Investing on electrical transport would benefit the environment a lot. Even more if this electricity came from a natural source of energy like wind, rivers and solar boards. We also have to take care of our rivers and seas. We all have heard about factories throwing highly toxic substances to rivers, without minimizing their poisoning effects. A really strict law should be applied to fine these factories and make them change their policy.

**Texto 2**  
Society has a responsibility to take care of the environment. We all live on this planet, so it's important for us to do our part to keep it clean and healthy. There are many things we can do to be environmentally responsible. We should recycle our waste, such as paper, plastic, and cans, instead of throwing them away. It's also important to save energy by turning off lights and appliances when we're not using them. Using public transportation or carpooling can help reduce pollution from cars. We should also avoid wasting water and try to conserve it. Planting trees and taking part in community clean-up activities are great ways to contribute to a cleaner environment. By being environmentally responsible, we can make a positive impact on our planet and ensure a better future for ourselves and future generations.

### Detectores de contenido generado por IA
https://undetectable.ai/  
https://gptzero.me/  
https://writer.com/ai-content-detector/  
https://platform.openai.com/ai-text-classifier  
https://contentatscale.ai/ai-content-detector/  
https://www.wordtune.com/ai-content-detector  
https://originality.ai/ (de pago)  

## Generación de material educativo

### Tarea  
Generar un texto sobre un tema y en un idioma a elección, para alumnos de nivel C1. A continuación, generar una lista de vocabulario, un ejercicio de verdadero/falso (5 ítems) y un multiple choice tipo cloze (10 ítems con 4 opciones c/u). ¿Cómo juzgarías la calidad? ¿Varía entre servicios?  

## Chatbots personalizados

### Tarea   
Crear un chatbot para automatizar la generación de contenido.  

**Gems:** https://gemini.google.com/gems/view  
**GPTs:** https://chatgpt.com/gpts (de pago)  

## Generación de imágenes y video  
### Tarea I  
Crear un poster para enseñar la hora en un idioma elegido. (ChatGPT)    

### Tarea II  
Generar un video sobre homófonos comunes del idioma, con ejemplos. Utilizar un GPT.  ([ejemplo](https://ai.invideo.io/watch/60WYDpmQWSV))

### Generadores de imágenes
**ChatGPT:** https://chat.openai.com/  
**Gemini:** https://gemini.google.com/  
**Google ImageFX:** https://labs.google/fx/tools/image-fx  
**Microsoft Designer:** https://designer.microsoft.com/image-creator  
**Stable Diffusion:** https://stablediffusionweb.com/#demo | https://stablediffusion.fr/xl  
**Openjourney 4:** https://huggingface.co/spaces/Yntec/ToyWorld  

# Recursos de alfabetización en IA

UNESCO: [AI competency framework for teachers](https://unesdoc.unesco.org/ark:/48223/pf0000391104)  
Creado por la UNESCO, este marco busca guiar a los profesores en el uso adecuado de la IA en la educación y fomentar su desarrollo profesional continuo.  

UNESCO: [AI competency framework for students](https://unesdoc.unesco.org/ark:/48223/pf0000391105)  
Desarrollado por la UNESCO, este marco tiene como objetivo preparar a los estudiantes para ser ciudadanos responsables y creativos en la era de la IA.  

British Council: [Human-centred AI: lessons for English learning and assessment](https://www.britishcouncil.org/research-insight/human-centred-ai-lessons-english-learning-assessment)  
Artículo que describe la posición del British Council en el uso de IA para el aprendizaje y evaluación de idiomas, con énfasis en el uso responsable y la ética.

[AI in 5 Minutes](https://www.aiedu.org/ai-in-five)  
Artículo súper corto que explica conceptos clave en IA.  

[How AI Works](https://code.org/ai#ai-videos)  
Videos introductorios cortos, fáciles y casuales sobre diferentes tareas dentro de la IA por expertos en el campo (OpenAI, Microsoft, Amazon, etc.). Buen punto de partida.  

[AI for Teachers](https://www.ai4t.eu/)
Un proyecto Erasmus+ K3 diseñado por Francia, Eslovenia, Italia, Irlanda y Luxemburgo para contribuir a la formación sobre IA en educación para y por profesores y líderes escolares. Contiene recursos útiles como artículos, un libro de texto sobre IA para profesores y una guía sobre cómo usar ChatGPT en educación por la UNESCO.  

[Elements of AI](https://www.elementsofai.com/eu2019fi)
Un curso de IA para principiantes desarrollado por el gobierno finlandés. Muy claro, en lenguaje sencillo, con excelentes elementos visuales y ejercicios. También se puede obtener un certificado de finalización. Disponible en todos los idiomas oficiales de la UE. Muy recomendable.

