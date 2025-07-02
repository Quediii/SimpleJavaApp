SimpleJavaApp

Prosta aplikacja REST w Javie z użyciem wbudowanego serwera HTTP. Projekt zawiera pipeline CI/CD z GitHub Actions oraz może zostać wdrożony np. na Render.com.

Uruchomienie lokalne

```bash
mvn compile
java -cp target/classes app.Main
```

Aplikacja będzie dostępna na `http://localhost:8080/`.

CI/CD

Automatyczne budowanie z wykorzystaniem GitHub Actions.

Deployment

Możesz wdrożyć aplikację na Render.com
