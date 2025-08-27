# Photo-Management-System-Data-structure-project-CSC212

## 📖 Description
A photo management application that enables users to add, delete, and organize photos by associating them with tags. Albums can be dynamically created based on tag conditions (e.g., "animal AND grass").  
To optimize search, an inverted index was implemented using a Binary Search Tree (BST).

## 🛠️ Technologies Used
- Java (without built-in collections)  
- Custom LinkedList implementation  
- Binary Search Tree (BST)  

## 🚀 Features
- Add and delete photos with tags  
- Create albums using tag conditions  
- Efficient tag-based search using BST-based inverted index  
- Performance improvement compared to linear search  

## ⚙️ Time Complexity (Highlights)
- **Before optimization (linear scan):** O(N * K * T)  
- **After optimization (BST inverted index):** O(K * log T + m)  
Where:  
- N = number of photos  
- K = number of tags in condition  
- T = number of unique tags  
- m = total photos in search results  
 
