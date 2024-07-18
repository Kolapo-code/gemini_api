Exercise Flow
These are the steps needed to complete the exercise:

Data Preparation: This step is completed for you. The files are loaded and unzipped in the notebook environment. You can also find a copy of these files in the downloadable Classroom resources.
Data Extraction and Summarization: Each file type requires some form of extraction before it can be used. For example, the text data is stored in image files, so you'll need to perform Optical Character Recognition (OCR). Then you'll use Gemini to generate summaries using a specialized prompt.
Embedding Generation: Once you have the text summaries, you'll use an embedding model to generate text embeddings.
Creating a Vector Database: Vector databases are effective for performing information retrieval tasks with text embeddings. We'll use Chroma DB.
Querying the Vector Database and Retrieval Augmented Generation: Finally, we'll write code that allows the system to retrieve the most relevant documents (based on their embeddings) and generate a response using the retrieved documents as context.
