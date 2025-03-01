I created this project during my third year at AGH University of Science and Technology, studying Informatics and Econometrics. This project represents only a part of the larger project that we worked on as a team, including Tomasz Zapart, Anna Rubin, Adrian Żyła, and Radosław Mocarski. Simulated Annealing was done only by myself, that's why I decided to upload it on my GitHub. The rest of the project can be viewed at https://github.com/RadandMoc/Inteligencja-Obliczeniowa.

# 🔥 (ENG) Simulated Annealing for TSP

## 📌 Project Overview
This project implements the **Simulated Annealing (SA) algorithm** to solve the **Traveling Salesman Problem (TSP)**. The algorithm is designed to find an approximate solution by gradually improving a candidate tour while avoiding local optima.

## 📂 Repository Structure

```
📦 Project Root
┣ 📂 .idea                     # IDE configuration files (ignore)
┣ 📜 Dane_TSP_127.csv          # TSP dataset (127 cities)
┣ 📜 Dane_TSP_48.csv           # TSP dataset (48 cities)
┣ 📜 Dane_TSP_76.csv           # TSP dataset (76 cities)
┣ 📜 SA.py                     # Simulated Annealing implementation
┣ 📜 Wyżarzanie_records_testy1.txt  # Test results
┣ 📜 README.md                 # Project documentation
```

## ▶️ Running the Algorithm
Run the **SA.py** script to execute the simulated annealing algorithm:
```sh
python SA.py
```

## 📊 Data Format
The `.csv` files contain **TSP instances**, where each cell represents distance between specific cities.

## ⚙️ Algorithm Overview
- **Initial Solution**: Randomly generates a tour.
- **Cooling Schedule**: Uses an exponential decay to lower the temperature.
- **Acceptance Probability**: Accepts worse solutions with a probability decreasing over time.
- **Stopping Condition**: Terminates when the temperature reaches a predefined threshold.

## 📝 Example Output
The algorithm outputs the best-found tour and its corresponding cost. Results are stored in `Wyżarzanie_records_testy1.txt`.

## 📌 Future Improvements
- 🏎️ Optimize the cooling schedule.
- 🤖 Implement parallel processing.
- 📈 Visualize TSP solutions.

---
Made by Mateusz Strojek 🚀

# 🔥 (PL) Wyżarzanie Symulowane dla TSP

## 📌 Opis Projektu  
Ten projekt implementuje algorytm **Wyżarzania Symulowanego (SA)** do rozwiązania **Problemu Komiwojażera (TSP)**. Algorytm znajduje przybliżone rozwiązanie poprzez stopniowe ulepszanie trasy, jednocześnie unikając lokalnych minimów.

## 📂 Struktura Repozytorium  

```
📾 Katalog Główny  
👉 📂 .idea                     # Pliki konfiguracyjne IDE (można zignorować)  
👉 📄 Dane_TSP_127.csv          # Zbiór danych TSP (127 miast)  
👉 📄 Dane_TSP_48.csv           # Zbiór danych TSP (48 miast)  
👉 📄 Dane_TSP_76.csv           # Zbiór danych TSP (76 miast)  
👉 📄 SA.py                     # Implementacja Wyżarzania Symulowanego  
👉 📄 Wyżarzanie_records_testy1.txt  # Wyniki testów  
👉 📄 README.md                 # Dokumentacja projektu  
```

## ▶️ Uruchamianie Algorytmu  
Aby uruchomić algorytm, wykonaj skrypt **SA.py**:  
```sh
python SA.py
```

## 📊 Format Danych  
Pliki `.csv` zawierają instancje **TSP**, gdzie każda komórka reprezentuje odległość między konkretnymi miastami.

## ⚙️ Opis Algorytmu  
- **Rozwiązanie początkowe**: Generowane losowo.  
- **Harmonogram chłodzenia**: Używa wykładniczego spadku temperatury.  
- **Prawdopodobieństwo akceptacji**: Akceptuje gorsze rozwiązania z malejącym prawdopodobieństwem.  
- **Warunek stopu**: Kończy działanie, gdy temperatura osiągnie określony próg.  

## 📝 Przykładowy Wynik  
Algorytm zwraca najlepsza znalezioną trasę i jej koszt. Wyniki są zapisane w `Wyżarzanie_records_testy1.txt`.

## 📌 Możliwe Ulepszenia  
- 🏃️‍♂️ Optymalizacja harmonogramu chłodzenia.  
- 🤖 Implementacja przetwarzania równoległego.  
- 📈 Wizualizacja rozwiązań TSP.  

---  
Autor: Mateusz Strojek 🚀


