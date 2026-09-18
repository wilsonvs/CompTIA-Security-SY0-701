# Soluções Criptográficas

## Objetivos
- Entender os conceitos criptográficos comuns
- Explicar criptografia, hashing, assinaturas digitais, certificados e PKI
- Relacionar a criptografia com confidencialidade, integridade, autenticação e não repúdio

## Sumário

1. [Criptografia](#criptografia)
2. [Criptografia (Encryption)](#criptografia-encryption)
3. [Criptografia Simétrica e Assimétrica](#criptografia-simétrica-e-assimétrica)
4. [Hashing](#hashing)
5. [Assinaturas Digitais](#assinaturas-digitais)
6. [Certificados e PKI](#certificados-e-pki)
7. [Casos de Uso Comuns da Criptografia](#casos-de-uso-comuns-da-criptografia)
8. [Gestão de Chaves](#gestão-de-chaves)
9. [Principais Conclusões](#principais-conclusões)

## Criptografia

- **Criptografia:** Técnicas usadas para proteger informações transformando-as ou provando sua autenticidade e integridade.
- A criptografia dá suporte à confidencialidade, integridade, autenticação e não repúdio.

## Criptografia (Encryption)

- **Encryption (Cifragem):** Converte dados legíveis em uma forma ilegível usando uma chave.
- **Texto Plano (Plaintext):** Dado original e legível.
- **Texto Cifrado (Ciphertext):** Dado criptografado e ilegível.
- **Descriptografia (Decryption):** Converte o texto cifrado de volta em texto plano usando a chave correta.

Exemplo:
- O disco de um notebook é criptografado para que os dados fiquem protegidos caso o notebook seja roubado.

## Criptografia Simétrica e Assimétrica

- **Criptografia Simétrica:** A mesma chave é usada para criptografar e descriptografar.
  - Mais rápida e útil para grandes volumes de dados.
  - Exemplo: AES.

- **Criptografia Assimétrica:** Usa um par de chave pública e chave privada.
  - A chave pública pode ser compartilhada.
  - A chave privada deve ser protegida.
  - Exemplo: RSA, ECC.

## Hashing

- **Hashing:** Converte dados em um valor de tamanho fixo.
- O hashing é unidirecional (one-way) e é usado para verificar integridade.

Exemplos:
- Verificar a integridade de um arquivo baixado
- Armazenar hashes de senha em vez de senhas em texto plano
- Comparar evidências sem alterar os dados originais

## Assinaturas Digitais

- **Assinatura Digital:** Usa criptografia para provar autenticidade, integridade e não repúdio.

As assinaturas digitais ajudam a provar:
- Quem assinou os dados
- Que os dados não foram alterados
- Que o remetente não pode facilmente negar ter assinado

## Certificados e PKI

- **Certificado:** Documento digital que vincula uma identidade a uma chave pública.
- **PKI (Public Key Infrastructure):** Infraestrutura de Chave Pública; sistema para criar, gerenciar, distribuir e revogar certificados.
- **CA (Certificate Authority):** Autoridade Certificadora; entidade confiável que emite certificados.

Os certificados são usados para:
- Sites HTTPS
- Autenticação de VPN
- Criptografia de e-mail
- Identidade de dispositivos
- Assinatura de código (code signing)

## Casos de Uso Comuns da Criptografia

- TLS para tráfego web seguro
- Criptografia de VPN
- Criptografia de disco completo (full-disk encryption)
- Criptografia de arquivos
- Hashing de senhas
- Assinaturas digitais
- E-mail seguro
- Autenticação baseada em certificado

## Gestão de Chaves

- As chaves devem ser protegidas, pois uma gestão de chaves fraca pode quebrar uma criptografia forte.

Boas práticas:
- Rotacionar as chaves
- Limitar o acesso às chaves
- Armazenar as chaves com segurança
- Revogar certificados comprometidos
- Separar funções na gestão de chaves
- Usar HSM ou cofre de chaves seguro quando apropriado

## Principais Conclusões

- A criptografia protege a confidencialidade.
- O hashing verifica a integridade.
- As assinaturas digitais dão suporte à integridade, autenticação e não repúdio.
- Certificados e PKI ajudam a estabelecer confiança.
