
# DESAFIO 2 - CRIAR UMA MÁQUINA VIRTUAL NO AZURE <BR>

### CRIAR UMA VM NO PORTAL AZURE <br>
As máquinas virtuais (VM) do Azure podem ser criadas por meio do Portal do Azure. Esse método fornece uma interface de usuário baseada em navegador para criar as VMS seus recursos relacionados. Esse início rápido mostra como usar o portal do Azure para implantar uma máquina virtual (VM) no Azure que executa o Windows Server 2022 Datacenter. Para ver a VM em ação, você habilita o protocolo RDP na VM e instala o servidor Web do IIS.


#### Entrar no Azure
  <https://portal.azure.com/>
<br>
<br>


#### Criar Máquina Virtual

1 - Digite máquinas virtuais na pesquisa.


2 - Em **Serviços**, selecione **Máquinas virtuais**.


3 - Na página **Máquinas virtuais**, clique em **Criar** e selecione **Máquina virtual do Azure**. A página Criar uma máquina virtual é aberta.
 
 
4 - Em **Detalhes da instância**, insira *myVM* no Nome da máquina virtual e escolha **Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2** na Imagem. Deixe os outros padrões.

<img width="808" height="378" alt="Instance_details" src="https://github.com/user-attachments/assets/41663e1f-75f0-4117-8493-b8fe8ec6c53b" />
<br>
<br>
<br>


Observação:
<br>
Alguns usuários agora verão a opção de criar VMs em várias zonas. 
Para saber mais sobre essa nova capacidade confira [Criar máquinas virtuais em uma zona de disponibilidade](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/faq#what-are-the-password-requirements-when-creating-a-vm/).

<img width="712" height="75" alt="Availability_Zone1" src="https://github.com/user-attachments/assets/5fbab531-d536-4801-846d-6b0f16825ce5" />
<br>
<br>
<br>



5 - Em **Conta de administrador**, forneça um nome de usuário, como *azureuser* e uma senha. A senha deve ter no mínimo 12 caracteres e atender a requisitos de complexidade definidos.
 
 <img width="746" height="147" alt="Administrador_account1" src="https://github.com/user-attachments/assets/96561b2d-d1f0-4f7d-92a9-e3283a0256b7" />
<br>
<br>



6 - Em **Regras de porta de entrada**, escolha **Permitir portas selecionadas** e, em seguida, selecione **RDP (3389)** e **HTTP (80)** na lista suspensa.

<img width="735" height="274" alt="Inbound_port_rules1" src="https://github.com/user-attachments/assets/68342415-dceb-44e9-b302-3bceec469b3e" />
<br>
<br>



7 - Deixe os padrões restantes e, em seguida, selecione o botão **Examinar + criar** na parte inferior da página.
<img width="549" height="256" alt="Review+Create1" src="https://github.com/user-attachments/assets/69e314ed-85b1-4ad6-8621-03443c778366" />
<br>
<br>


8 - Após a execução da validação, selecione o botão **Criar** na parte inferior da página.
<img width="537" height="489" alt="Create_virtual_machine1" src="https://github.com/user-attachments/assets/0ce926cb-e8e2-4d92-9a9a-1aa37c98ed27" />
<br>
<br>


9 - Após a conclusão da implantação, selecione **Ir para o recurso**.

<img width="442" height="156" alt="Go_to_resource1" src="https://github.com/user-attachments/assets/d6d3073b-c082-4cab-bfec-d21e251f6722" />
















