

🎬 **IMDB Upload** 🎥

IMDB Upload is a scalable web application designed for efficient processing and management of large-scale movie data uploads. Built on Flask and MongoDB, it provides robust functionality for uploading movie data via CSV files, real-time progress tracking, and displaying paginated movie lists with advanced sorting options.

### Key Features:
- **Scalable Architecture**: Leveraging Flask and MongoDB, IMDB Upload is engineered for scalability, capable of handling large CSV files with up to 10 GB of data and billions of rows.
- **Efficient Upload Processing**: Utilizing pre-signed URLs, files are uploaded directly to Amazon S3, bypassing the server and minimizing resource consumption for faster and more efficient processing.
- **Real-time Progress Tracking**: Users can monitor the progress of their file uploads in real-time, providing transparency and insight into the status of their data submissions.
- **Advanced Sorting and Pagination**: The application offers extensive sorting capabilities, allowing users to sort movie lists based on various parameters such as Date Added, Release Date, and Duration, with seamless pagination for improved navigation and user experience.

### Tech Stack:
- **Backend**: Flask, PyMongo
- **Frontend**: HTML, JavaScript
- **Database**: MongoDB
- **Storage**: Amazon S3
- **Deployment**: Docker, AWS (optional)

### Usage:
1. Clone the repository: `git clone https://github.com/username/imdb-upload.git`
2. Set up a virtual environment and install dependencies: `pip install -r requirements.txt`
3. Configure MongoDB and Amazon S3 credentials in the Flask application.
4. Run the Flask application: `python app.py`
5. Access the application in your browser at `http://localhost:5000`

### Contribution:
Contributions are encouraged! Developers can contribute to the project by opening issues, submitting pull requests, or suggesting enhancements to improve the application's functionality and performance.
