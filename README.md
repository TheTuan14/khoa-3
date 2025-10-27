#css

body {
  font-family: Arial, sans-serif;
  background-color: #f0f4f8;
  text-align: center;
  padding: 20px;
}

.gallery {
  display: flex;
  justify-content: center;
  gap: 15px;
}

.gallery img {
  border: 3px solid transparent;
  border-radius: 10px;
  transition: all 0.3s ease;
  cursor: pointer;
}

.gallery img:hover,
.gallery img:focus {
  border-color: #007bff;
  transform: scale(1.05);
  outline: none;
}

