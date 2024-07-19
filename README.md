![apollo-11](https://github.com/user-attachments/assets/56d57a4f-aebc-4fb5-8be9-84e295b192c9)
Project Flow

These are the steps needed to complete the project:

Data Preparation: The files are loaded and unzipped in the notebook environment.
Data Extraction and Summarization: Each file type requires some form of extraction before it can be used. For example, the text data is stored in image files, so there is need to perform Optical Character Recognition (OCR). Then use Gemini to generate summaries using a specialized prompt.
Embedding Generation: Once have the text summaries, use an embedding model to generate text embeddings.
Creating a Vector Database: Vector databases are effective for performing information retrieval tasks with text embeddings. Use Chroma DB.
Querying the Vector Database and Retrieval Augmented Generation: Finally, write code that allows the system to retrieve the most relevant documents (based on their embeddings) and generate a response using the retrieved documents as context.
