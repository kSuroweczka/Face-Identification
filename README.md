# Identyfikacja osób z zasłoniętą dolną połową twarzy 
Projekt podzielony został na 4 notatniki Google Colab:
1. mask_detection_model - model TensorFlow do wykrywania masek na twarzy, pobranie i przygotowanie zestawu danych treningowych, walidacyjnych i testowych, budowa modelu, trening z użyciem augmentacji obrazu
2. data_preprocessing - wykrywanie twarzy przy użyciu Haar Cascades, ekstrakcja górnej części twarzy w przypadku obecności maseczki, wykrywanie masek za pomocą wytrenowanego modelu, przetwarzanie klatek z wideo oraz dzielenie danych na zestawy treningowe i testowe
3. face_recognition_model - generowanie osadzeń dla obrazów twarzy, tworzenie i trening modelu rozpoznającego osoby z bazy, ocena i testy modelu
4. final_results - prezentacja wyników na zdjęciach osób z i spoza bazy

### Aby otworzyć każdy z notatników należy:
1. Otworzyć Google Colab w przeglądarce.
2. Wybrać opcję "Github" i wkleić adres URL repozytorium.
3. Wybierać odpowiedni notatnik z listy wyników wyszukiwania
4. Jeśli notatnik wymaga plików danych, które są dostępne w repozytorium GitHub, należy je pobrać ręcznie i dodać do notatnika.

W każdym z notatników wskazane są konkretne pliki, które muszą być załadowane, aby program działał prawidłowo. Wszystkie wymagane pliki znajdują się w folderze DATA (również te wygenerowane w trakcie realizacji projektu).  
