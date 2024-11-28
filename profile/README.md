# t1.msk Hackathon 2024

## Team: reshAI 2.0

### Track: "Knowledge Window: Digital Knowledge Base Assistant"

---

### Project Overview

The goal of our project is to create a platform that allows companies to quickly and seamlessly integrate their knowledge bases with digital assistants, providing customizable and efficient interaction windows for users. This solution is designed to improve user access to information while addressing integration challenges and enabling customization.

---

### Planned Solution Architecture

![Planned Solution Architecture](http://d.zaix.ru/KcgE.png)

The planned architecture consists of the following components:

1. **Admin Panel Web Interface**:

   - A user-friendly interface for administrators to configure and manage the system.

2. **Importapi**:

   - A service for importing and extracting text from various sources (e.g., txt, pdf, docx, URLs).

3. **Vector Database**:

   - A storage solution optimized for vector representations of knowledge base content.

4. **LLM (Large Language Model)**:

   - Provides natural language processing capabilities for querying and interacting with the knowledge base.

5. **Chat bot**:

   - A user-facing chat window for interacting with the assistant.

---

### Current Project Status

The following components have been implemented:

1. **importapi**

   - An API designed for importing and extracting text from various sources, including:
     - Text files (txt)
     - PDFs
     - Word documents (docx)
     - URLs

2. **admin-ui**

   - A web-based interface for configuring the admin panel.

3. **chatbot**

   - A chat window for user interactions with the assistant.

---

### Hackathon Requirements

#### Business Requirements:

1. **Data Integration**:

   - Support for multiple knowledge base formats, such as text documents (pdf, docx, txt), URLs, and platforms like Notion and Confluence.

2. **Neural Network Training**:

   - Utilize the knowledge base data to provide accurate and context-aware responses.

3. **Interface Customization**:

   - Enable changes to colors, fonts, and logos to align with a company’s branding.

4. **Multimodality**:

   - Ensure compatibility across different devices and data formats.

#### Non-Functional Requirements:

- **Performance**: Efficient processing of large datasets without compromising speed.
- **Scalability**: Handle increasing request volumes.
- **Security**: Protect user data and ensure confidentiality.
- **Usability**: Intuitive design for all interface components.
- **Independence**: Avoid reliance on external services or libraries unsuitable for commercial use.

#### Evaluation Criteria:

1. Functional requirement compliance (40%)
2. Prototype functionality (30%)
3. Technological innovation (10%)
4. Intuitive interfaces (10%)
5. Scalability (5%)
6. Data security (5%)

---

### Next Steps

- Complete the integration of all planned components.
- Conduct testing to ensure performance, scalability, and security.
- Prepare the final demo and documentation for submission.

---

### Contact

For further details or questions, please contact the reshAI 2.0 team

