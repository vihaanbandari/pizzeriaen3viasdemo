# Wasmer Deploy Steps

1. Install and login:
   - `wasmer login`
2. In this project folder, update:
   - `wasmer.toml` -> replace `your-wasmer-username` in `name`
   - `app.yaml` -> replace `owner` and `package` with your Wasmer username
3. Run local test:
   - `wasmer run . -- --port 9000`
4. Deploy:
   - `wasmer deploy`

## Files included for deploy

- `public/index.html`
- `public/styles.css`
- `public/assets/*`
- `wasmer.toml`
- `app.yaml`
