# PROJETO 1 - Laboratório Pessoal para Prática de Segurança Ofensiva (Penetration Testing)

## Objetivo:
Criar um ambiente virtual isolado para simular ataques e testar técnicas de segurança ofensiva.

## Sistemas Utilizados:
- **[VirtualBox](https://www.virtualbox.org/)**
- **Windows 10**
- **Kali Linux**

## Descrição do Projeto:

### Fase 1 - Criação do Ambiente Virtual
**Configuração de máquinas virtuais utilizando o [VirtualBox](https://www.virtualbox.org/):**
- Download e instalação das [imagens oficiais do Kali Linux](https://www.kali.org/get-kali/#kali-virtual-machines) (penetration testing) e Windows 10 (máquina alvo).
- Atualização e configuração dos sistemas para replicar um cenário realista de redes corporativas.

### Fase 2 - Configuração de Redes Isoladas
**Implementação de uma rede Host-Only para isolar o tráfego interno e prevenir vazamento de malwares durante os testes:**
- Criação da rede virtual via VirtualBox.
- Alocação das máquinas nas redes correspondentes (Kali Linux como atacante e Windows 10 como alvo).
- Configuração adicional de uma rede pública temporária para atualização e download de ferramentas quando necessário.

## Habilidades Desenvolvidas:
- Virtualização de sistemas (VirtualBox)
- Configuração e administração de redes (Host-Only, redes públicas)
- Prática de segurança ofensiva em ambientes controlados
- Uso de ferramentas de penetration testing (Kali Linux)
- Conceitos de isolamento de redes e mitigação de riscos
