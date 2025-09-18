# 📱 Scanner NF-e

Aplicativo web para escanear códigos de barras e QR codes de Notas Fiscais Eletrônicas pelo celular.

## 🚀 Funcionalidades

- ✅ Escaneamento via câmera do celular
- ✅ Suporte a QR codes e códigos de barras
- ✅ Validação automática de chaves NFe (44 dígitos)
- ✅ Envio por email com template profissional
- ✅ Interface responsiva e moderna
- ✅ Funcionamento offline (PWA)
- ✅ Input manual como alternativa

## 📱 Como Usar

1. Acesse o aplicativo no navegador do celular
2. Clique em "Iniciar Scanner"
3. Permita acesso à câmera
4. Aponte para o código da NFe
5. O email será preparado automaticamente

## 🛠️ Teste Local

```bash
# Inicie um servidor local
python -m http.server 8080

# Acesse no celular (mesma rede Wi-Fi)
http://SEU_IP_LOCAL:8080
```

## 📧 Configuração

O email é enviado para: `vitoraugusto@agalogistica.com.br`

Para alterar, edite a linha 269 no `index.html`.

## 🔧 Tecnologias

- HTML5 + CSS3 + JavaScript
- html5-qrcode library
- Service Worker (PWA)
- Responsive Design
