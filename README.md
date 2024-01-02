# Identyfikacja osób z zasłoniętą dolną połową twarzy 
Projekt podzielony został na 3 notatniki Google Colab:
* data preprocessing - wykrywanie twarzy przy użyciu Haar Cascades, ekstrakcja górnej części twarzy w przypadku noszenia masek, wykrywanie masek za pomocą wytrenowanego modelu, przetwarzanie klatek z wideo oraz dzielenie danych na zestawy treningowe i testowe
* mask_detection_model - model TensorFlow do wykrywania masek na twarzy, pobranie i przygotowanie zestawu danych treningowych, walidacyjnych i testowych, budowa modelu, trening z użyciem augmentacji obrazu
* face_recognition_model - generowanie osadzeń dla obrazów twarzy, tworzenie i trening modelu rozpoznającej osoby, z bazy, ocena i testy na obrazach spoza datasetu

W każdym z notatników wskazane są konkretne pliki, które muszą być załadowane, aby program działał prawidłowo. Wszystkie wymagane pliki znajdują się w folderze DATA (również te wygenerowane w trakcie realizacji projektu).
