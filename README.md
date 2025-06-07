# -resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Durante o lab sobre nuvem, alguns pontos ganham destaque e merecem atenção especial. Eles formam a base para entender como tudo funciona quando falamos sobre modelo de nuvem:
Tipos de nuvem – entendendo o básico
Nuvem privada pressupõe que tudo fica dentro da empresa. A infraestrutura roda em um datacenter privado, com controle total sobre segurança, acesso, atualizações e manutenção.
Na nuvem pública um provedor oferece recursos para várias empresas e usuários. Você acessa pela internet, usa o que precisa e paga só pelo que usar(como o Azure)
Nuvem híbrida como sendo a junção dos dois mundos. A empresa pode usar tanto a nuvem privada quanto a pública, conectando as duas de forma inteligente para rodar os sistemas onde for melhor.
No contexto de multinuvem (Multicloud) a empresa usa vários provedores ao mesmo tempo (como Azure + AWS). Isso dá mais liberdade e evita depender só de um fornecedor.

💸 CapEx x OpEx – o jeito de gastar muda
CapEx (Despesas de capital)É o modelo antigo: comprar servidores, investir pesado em ar-condicionado, energia, manutenção, etc. Um gasto grande de uma vez só.
OpEx (Despesas operacionais)É o modelo da nuvem: paga conforme usa. Sem grandes investimentos iniciais, só o custo mensal do que você realmente está usando.

📊 Modelo de consumo
Na nuvem, o modelo é sob demanda: usou, pagou. Não usou, não paga. Isso deixa tudo mais econômico e escalável, ideal pra testar ideias rápido sem precisar montar uma estrutura cara.

🧱 Criando recursos no Azure
A princípio você recebe créditos grátis por 30 dias pra explorar a plataforma;
Nem todos os serviços ficam disponíveis pra contas com limite menor ou em certas regiões;
O portal é bem visual e organizado por categorias (rede, banco, apps, etc), e você pode personalizar a interface (tema, idioma...).

🔐 Segurança e rede
Azure Bastion: acesso seguro às máquinas virtuais, sem precisar abrir portas externas,como um servidor ponte (jumpserver).
O Azure também oferece recursos como peering de rede, gateways, WANs virtuais, redes móveis e muito mais.

🧪 Serviços em versão preview
Alguns serviços ainda em fase de testes (versão prévia). É possível experimentar, mas eles ainda podem mudar ou ter limitações.
