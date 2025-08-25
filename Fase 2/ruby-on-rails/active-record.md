### 🗄️ **2.2 Banco de Dados e Active Record**

| Conceito | Descrição | Comando/Exemplo |
|----------|-----------|-----------------|
| **📋 Migrations** | Versionamento do BD | `rails generate migration` |
| **🔗 Active Record** | ORM do Rails | `User.find(1)` |
| **🤝 Associations** | Relacionamentos | `has_many`, `belongs_to` |
| **✅ Validations** | Regras de negócio | `validates :email, presence: true` |

#### 📝 **Projeto Prático:**
```ruby
# Sistema de blog com comentários:
# ✅ Post has_many :comments
# ✅ Comment belongs_to :post
# ✅ Validações em ambos models
# ✅ Seeds para dados de teste
```