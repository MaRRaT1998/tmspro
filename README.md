# TMS PRO – Profesjonalny System Zarządzania Transportem

## Funkcje
- Rejestracja i logowanie użytkowników
- Import pełnych danych ze zleceń z PDF (AI)
- Raporty wg dat rozładunku
- Integracja: Google Maps, Infakt, AI (OCR/Extraction)
- Panel instalacyjny z konfiguracją kluczy API
- Baza danych PostgreSQL
- Nowoczesny frontend (React + Material UI)
- Backend (Python FastAPI)

## Instalacja
1. Zainstaluj PostgreSQL (i Node.js oraz Python 3.10+)
2. Uruchom skrypt instalacyjny:  
   ```bash
   bash installer/install.sh
   ```
3. Przejdź do `http://localhost:8000/install` i wypełnij panel instalacyjny (klucze API, admin)
4. Frontend:  
   ```bash
   cd frontend
   npm start
   ```
5. Backend:  
   ```bash
   cd backend
   uvicorn main:app --reload
   ```

## Dostęp do panelu:  
`http://localhost:3000`

---

## Struktura katalogów

- backend/
- frontend/
- installer/
