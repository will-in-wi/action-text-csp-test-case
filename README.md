# Test case for bug

This was generated with:
```bash
rails new action_text_csp
cd action_text_csp/
rails action_text:install
rails g scaffold post title:string
rails db:migrate
```
