# Model de Dades

## Model Entitat Relació E/R

```mermaid
erDiagram
    user ||--o{ post : id
    user {
        string username
        string password
       
    }
    post ||--|{ user : id
    post {
        date created
        string title
        string body
       
    }
   

