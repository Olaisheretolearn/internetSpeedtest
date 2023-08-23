## 🚀 Internet Speed Test

An intuitive and user-friendly tool to help users check their internet download and upload speeds.

### 📸 Preview
live preview at https://zappyzap.netlify.app/


### 🧠 How It Works

The Internet Speed Test measures the download speed by fetching a predefined image or file from a server. The time taken to complete this download helps calculate the speed of the internet connection.

Similarly, for measuring upload speeds, a predefined set of data is sent to a server, and the time taken provides a measure of the upload speed.

### ⚙️ The Science Behind It

#### Download Speed

The tool fetches a file of known size from a server. By measuring the time it takes to download and dividing it by the file size, we get the speed of the connection.


### 🚫 Caching Issue & Solution

During initial tests, it was observed that browsers often cache files that have been downloaded. This caching meant that subsequent speed tests, instead of fetching the file from the server, would retrieve it from the cache, leading to inaccurately high speed results.

**Solution**: To overcome this caching problem, a unique parameter (typically a timestamp) is appended to the file URL each time a speed test is initiated. This ensures that the file is freshly fetched from the server every time, giving accurate speed results.

### 📂 Setup and Usage

1. Navigate to the project directory:
```bash
cd path-to-your-project-directory
```
2. Open index.html in your preferred browser to run the speed test.

###🤝 Contributing

We welcome contributions from the community. If you'd like to improve the Internet Speed Test tool, please fork the repository and make your changes. Then submit a pull request.

###🔒 License

This project is licensed under the MIT License. See the LICENSE file for details.
🙋‍♂️ Support

If you encounter any issues or have questions, please open an issue.

