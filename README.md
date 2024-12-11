# GarbhaKalyani - Ayurvedic Prenatal Chatbot

## Overview
GarbhaKalyani is an AI-powered chatbot designed to provide holistic and personalized Ayurvedic prenatal care. This project integrates the ancient wisdom of Ayurveda with advanced artificial intelligence to offer accessible, safe, and context-aware advice for pregnant women. It leverages Retrieval-Augmented Generation (RAG) and GPT-based models to deliver recommendations tailored to the user's pregnancy stage, health conditions, and Ayurvedic constitution (Prakriti).

---

## Features

1. **Personalized Prenatal Care:**
   - Tailored advice on diet, exercise, emotional well-being, and herbal remedies.
   - Advanced insights on epigenetics and nutrigenomics.

2. **Technology Stack:**
   - GPT-based conversational AI.
   - Retrieval-Augmented Generation (RAG) system for context-aware recommendations.
   - LangChain, ChromaDB, and LangGraph for conversational modeling and document retrieval.

3. **User-Centric Design:**
   - Stateful memory management for multi-session conversations.
   - Interactive conversational flow using graph-based state transitions.

4. **Evaluation Metrics:**
   - High performance across faithfulness, context recall, and relevancy scores.

---

## Methodology

### System Architecture
- **LangChain** for conversational modeling.
- **ChromaDB** for efficient document retrieval.
- **LangGraph** for managing dialogue flow and state transitions.
- **Stateful Memory:** Ensures continuity over multiple conversational turns.

### Prompt Engineering
- Techniques include zero-shot, few-shot, chain-of-thought, and context-based prompting.
- Context-based prompting paired with RAG yielded the best results.

### Evaluation
- Metrics such as precision, recall, and F1 scores were used to assess system performance.
- Comparative analysis with other systems highlighted GarbhaKalyani’s superior accuracy and relevancy.



## How to Run

1. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Setup ChromaDB:**
   - Add Ayurvedic health-related data to the database.

3. **Run the Chatbot:**
   ```bash
   python chatbot.py
   ```

4. **Interact with the Chatbot:**
   - Input queries related to prenatal care to receive personalized Ayurvedic advice.

---

## Future Enhancements

1. **Memory Implementation:**
   - Enable long-term memory for multi-session interactions.
2. **Voice-Based Interaction:**
   - Add support for voice commands and responses.
3. **User Testing:**
   - Deploy the chatbot for broader testing and feedback.

---

## Contributing
We welcome contributions to improve GarbhaKalyani. Please follow these steps:

1. Fork this repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add a new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

---

## Authors
- **Sarthak Ingle** ([f20220037@pilani.bits-pilani.ac.in](mailto:f20220037@pilani.bits-pilani.ac.in))
- **Rudresh Joshi** ([f20220159@pilani.bits-pilani.ac.in](mailto:f20220159@pilani.bits-pilani.ac.in))
- **Asst. Prof. Dhruv Kumar** ([dhruv.kumar@pilani.bits-pilani.ac.in](mailto:dhruv.kumar@pilani.bits-pilani.ac.in))

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## References
Please refer to the `References` section in the report for detailed academic and technical sources.

