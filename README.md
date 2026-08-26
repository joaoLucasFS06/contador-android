# Nome
- João Lucas Ferreira Souza

# Explicação
- O estado do app é armazenado na variável `contador`, criada com `remember { mutableStateOf(0) }`.
- Quando o usuário clica nos botões, `contador++` ou `contador--` altera esse estado.
- O Jetpack Compose detecta a mudança e recompõe a interface, atualizando o `Text` com o novo valor.
- O `remember` mantém o valor durante as recomposições do componente.

#
<img height="720" alt="Screenshot_20260825_231904" src="https://github.com/user-attachments/assets/1d84d702-d95e-4b91-af1f-5c9e43628c86" />
