# Zadanie: Zaprojektuj API do zarządzania adresami dostaw i produktami w zamówieniu

## Wymagania biznesowe

- **Order.address**: Reprezentuje domyślny adres klienta.
- **Model Logistic**: Odpowiada za wysyłkę produktów do klienta.

Zaprojektuj API, które umożliwi edycję adresu klienta dla wybranych produktów zamówienia.

Często zdarza się, że klient chce wysłać część produktów na inny adres. 

W takim przypadku należy przenieść wybrane produkty do nowego obiektu Logistic z właściwym adresem.

---

### Funkcjonalność API

API powinno umożliwiać:

- zmianę adresu dostawy dla wybranych produktów,

---

### Audyt zmian (śledzenie historii)

System powinien rejestrować każdą wykonaną operację, w tym:

- typ operacji (np. zmiana adresu, usunięcie produktu),
- szczegóły zmian (adresy, identyfikatory produktów),
- czas wykonania operacji.

---
