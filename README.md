# QA-with-LLMs
Implementación de un algoritmo de Question Aswering (QA) sobre el cuento "Emma Zunz" de Jorge Luis Borges y sobre el texto histórico "El 45", de Félix Luna.

A partir de la utilización de LangChain, un framework que permite interactuar con diversos modelos de lenguajes (LLMs), exploraremos la implementación de una secuencia de QA con dos de los posibles métodos existentes: en primera instancia, utilizando VectorstoreIndexCreator; en segunda instancia, utilizando load_qa_chain y ConversationalRetrievalChain.

## Conclusiones

Las herramientas utilizadas para llevar a cabo el ejercicio de Question Answering sobre estos dos textos tan plausibles como diferentes, ha demostrado tener un gran nivel de acertividad. Si bien se detectan errores, se pudo comprobar que los mismos disminuyen considerablemente toda vez que es brindado un contexto concreto y se reduce al mínimo la redundancia o la potencial doble interpretación. De todos modos, se ha demostrado que en instancias de incertidumbre mayor, el framework logra responder nuestras preguntas con muy aceptables niveles de tolerancia.
Asimismo, hemos experimentado diversos métodos, cada uno de ellos apoyado sobre las características del texto sobre el que serían implementados. Mientras que el primero, VectorstoreIndexCreator, muestra una excelente performance -aunque con algunos errores- sobre textos más pequeños que no requieren ser "batcheados", load_qa_chain y ConversationalRetrievalChain demostraron ser mucho más eficientes en cadenas mucho más largas y complejas.

Puede acceder a la notebook desde [aquí](https://github.com/nachotitimoli/QA-with-LLMs/blob/main/QA%20with%20LLMs.ipynb).
