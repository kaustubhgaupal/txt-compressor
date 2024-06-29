# txt-compressor

This web application uses Huffman Coding for text compression and decompression. Made with JavaScript, HTML, and CSS.

## About this application:

**txt-compressor** is an online tool for compressing and decompressing text (.txt) files using the Huffman Algorithm. This tool can reduce file sizes by 35% to 50%, ensuring efficient storage and transfer.

### Key Features:
- **Huffman Coding:** The tool assigns variable-length codes to characters based on their frequency of occurrence. More frequent characters get shorter codes, and less frequent characters get longer codes.
- **Compression:** Compresses text files by converting characters to Huffman codes, significantly reducing file size.
- **Decompression:** Decodes the compressed files back to their original size.
- **Security:** Enhances file security by encoding the text during compression, making it less readable without decompression.
- **Implementation:** Uses JavaScript for the algorithms and HTML/CSS for a responsive design.
- **Instructions and Warnings:** Provides additional instructions and warnings if the steps are not followed correctly.
- **Info Page:** Includes a page with detailed information about the technique of lossless data compression using Huffman coding.

### How it Works:
1. **Compression:**
   - Upload a text (.txt) file.
   - The application reads the file and calculates the frequency of each character.
   - A binary tree is constructed based on the frequencies, with the most frequent characters assigned the shortest codes.
   - The characters are replaced with their respective Huffman codes, compressing the file size by 35% to 50%.
   
2. **Decompression:**
   - Upload a compressed file.
   - The application decodes the file using the Huffman tree to restore it to its original size and content.

### Usage:
1. Upload a text file to compress.
2. Download the compressed file.
3. Upload the compressed file to decompress it back to the original text.

### Technologies Used:
- **JavaScript:** Implements the Huffman coding algorithm.
- **HTML:** Structures the web page.
- **CSS:** Styles the web page to be responsive and user-friendly.

### Additional Notes:
- Ensure you follow the instructions provided on the website for optimal performance.
- For more information about Huffman coding and lossless data compression, visit the Info page on the website.

Enjoy efficient and secure text file compression with txt-compressor!


