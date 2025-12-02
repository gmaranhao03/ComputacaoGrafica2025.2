\# Documentação do trabalho Blender





\## 1) Conceito

A intenção era criar um espaço que mesclasse o conforto de uma cabana com a funcionalidade de um espaço de trabalho moderno, com atmosfera aconchegante. O contraste entre o busto clássico e o monitor de computador mesclam arte tradicional quanto a tecnologia digital.



\## 2) Materiais e Propriedades PBR

A texturização seguiu o fluxo de trabalho PBR (Physically Based Rendering).



\* \*\*Madeira (Mesa, Divisória Orgânica, Gaveteiro e Teto)\*\*

\* \*\*Paredes de plaster\*\*

\* \*\*Tecidos (Cortinas):\*\* Uso de Subsurface Scattering nas cortinas para permitir a passagem difusa da luz externa.



\## 3) Sistema de Iluminação

\*  \*\*Luz Principal:\*\* Uma fonte de luz (Sun Light), simulando um sol baixo de Golden Hour. Ela entra pela janela e cria as sombras marcadas.

\*  \*\*Luz Ambiente:\*\* Um mapa HDRI de intensidade baixa foi usado para preencher as sombras profundas, equilibrando o calor da luz direta e das luzes internas.

\*  \*\*Luzes Práticas:\*\* O varal de luzes no teto Configuradas como Emission Shaders.



\## 4) Trajetória e Conceito da Animação de Câmera

\* A animação tem Início em wide shot mostrando o quarto e depois passa para um medium shot focado na mesa de trabalho, finalizando com o foco no monitor e no busto.

\* O foco foi mantido fixo na área da mesa, permitindo que o primeiro plano e o fundo ficassem desfocados no início.



\## 5) Desafios e Soluções

\* Ruído na Renderização (Noise): O uso de muitas pequenas fontes de luz (o varal no teto) em um ambiente fechado gerou ruído nas áreas de sombra.

&nbsp;   \* \*Solução:\* Aumento das samples e uso de denoising.

\* Equilíbrio de Exposição: Balancear a luz externa forte com a luz fraca do varal interno.

&nbsp;   \* \*Solução:\* Uso de "False Color" para verificar áreas estouradas e ajuste da exposição da câmera



\## 6) Referências Visuais

\* Estética Lo-Fi, Design Escandinavo Rústico.

\* Iluminação Fotografia de interiores Moody e setups de setups de mesa do Pinterest/Instagram.

