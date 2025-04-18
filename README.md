# 📦 Projet Spring Boot - Gestion de Dons

Ce projet est une application web développée avec **Spring Boot** permettant de gérer des campagnes de dons.  
Elle inclut une API REST permettant d'enregistrer des dons associés à des campagnes, avec stockage en base de données **H2 en mémoire**.

---

## 🚀 Fonctionnalités

- 🔍 CRUD des campagnes de dons
- 💸 Ajout de dons liés à une campagne
- 📅 Enregistrement de la date, du montant et du nom du donateur
- 🧾 API REST exposée avec Spring Web
- 🗄️ Base de données H2 embarquée + Console H2 activée
- ✅ Validation des données via `@Valid` et DTOs

---

## 🛠️ Stack technique

- Java 17+
- Spring Boot 3+
- Spring Web
- Spring Data JPA
- H2 Database
- Maven

---

## 🧪 Lancer l'application

### Prérequis
- Java installé (version 17 ou plus)
- Maven installé

### Commandes

```bash
# Cloner le projet
git clone https://github.com/tonUser/tonRepo.git
cd tonRepo

# Lancer l'application
./mvnw spring-boot:run
