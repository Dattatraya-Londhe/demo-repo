# demo-repo
Testing Purpose

# Modification -first time
Dattatraya Londhe

```prisma
model User {
  id        Int      @id @default(autoincrement())
  createdAt DateTime @default(now())
  email     String   @unique
  name      String?
}
```
