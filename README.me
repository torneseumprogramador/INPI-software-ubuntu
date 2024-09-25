

# Documentação: Gerar Hashes de um Arquivo ZIP no Ubuntu

## Objetivo
Este documento descreve os passos para gerar os hashes SHA-224, SHA-256 e SHA-512 de um arquivo ZIP utilizando um shell script no Ubuntu.

## Pré-requisitos
- Um sistema Ubuntu (ou similar) instalado.
- Um arquivo ZIP para gerar os hashes.
- Acesso ao terminal.

## Passos para Gerar os Hashes

### 1. Verifique se as Ferramentas de Hash estão Instaladas

Por padrão, o Ubuntu deve vir com as ferramentas de hash (como `sha256sum` e `sha512sum`) instaladas. Para verificar, execute os seguintes comandos no terminal:

```bash
sha256sum --version
sha512sum --version
```

Se eles não estiverem instalados, você pode instalá-los usando o comando:

```bash
sudo apt update
sudo apt install coreutils
```

### 2. Criação do Script Shell

#### 2.1. Crie o Arquivo do Script

Abra um terminal e crie um novo arquivo chamado `gerar_hashes.sh`:

```bash
nano gerar_hashes.sh
```

#### 2.2. Adicione o Conteúdo do Script

Dentro do arquivo, adicione o seguinte código:

```bash
#!/bin/bash

# Nome do arquivo ZIP
ARQUIVO_ZIP="seu_arquivo.zip"

# Verifica se o arquivo existe
if [ ! -f "$ARQUIVO_ZIP" ]; then
    echo "Arquivo $ARQUIVO_ZIP não encontrado!"
    exit 1
fi

# Gerar o hash SHA-224 (utilizando openssl, pois sha224sum pode não estar disponível)
echo "Gerando hash SHA-224..."
openssl dgst -sha224 "$ARQUIVO_ZIP"

# Gerar o hash SHA-256
echo "Gerando hash SHA-256..."
sha256sum "$ARQUIVO_ZIP"

# Gerar o hash SHA-512
echo "Gerando hash SHA-512..."
sha512sum "$ARQUIVO_ZIP"
```

Salve e feche o arquivo (`CTRL + X`, depois `Y` e `ENTER`).

#### 2.3. Torne o Script Executável

No terminal, execute o seguinte comando para garantir que o script tenha permissão de execução:

```bash
chmod +x gerar_hashes.sh
```

### 3. Executando o Script

Agora você pode executar o script passando o nome do arquivo ZIP para gerar os hashes:

```bash
./gerar_hashes.sh
```

**Saída esperada**: O script vai gerar e exibir os hashes SHA-224, SHA-256, e SHA-512 do arquivo ZIP.

Exemplo de saída:

```plaintext
Gerando hash SHA-224...
SHA224(seu_arquivo.zip)= 65307cb3f89bfd964402535eeaf247c294f9da508760592096ebd521
Gerando hash SHA-256...
4ecc1869d3babd73136366d79199a7dde5ddc3ae5050b547915df84a60f91130  seu_arquivo.zip
Gerando hash SHA-512...
54ef251f818d81132f0134a3aba009cbc16a16033299637c7668eda3644cffdd5e5c89a77efd95d675404a10e0b1109a977fa8bcec0b83b884796fd383a46d27  seu_arquivo.zip
```

### 4. Solução Alternativa para SHA-224

Caso o comando `sha224sum` não esteja disponível no seu sistema, você pode gerar o hash SHA-224 utilizando o comando `openssl` como demonstrado no script acima.

```bash
openssl dgst -sha224 nome_do_arquivo.zip
```

### 5. Debugging e Verificação

- Se você encontrar erros ao tentar executar o script, verifique se o arquivo ZIP existe e se o caminho está correto.
- Certifique-se de que você tem permissões de leitura para o arquivo ZIP e permissões de execução para o script.

### 6. Encerramento

Agora você pode gerar os hashes para qualquer arquivo ZIP que você tenha, o que é especialmente útil para registro em órgãos como o INPI, onde é necessário fornecer esses hashes para fins de autenticação e validação de propriedade.
