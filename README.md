# Controller Web - Estilo Visual
Padrão de Design Genexus ControllerWeb

* Data Criação : **10/01/2018**

[ ] - Utilização de ícons padrão Glyphicon e FontAwesome;

[ ] - Melhorar segurança(conforme papeis) dos Menus superiores;

[ ] - Aprovar Menu com Edward;

***

1. Padrão dos CRUDS(insert, update, delete) com Pattern wwplus;
   
   * A classe do botão é "bottom_actions" , bottom com m

   ![alt tag](https://jjriug-dm2305.files.1drv.com/y4m7bvGxHPRx8gU1KYEVXb3VPEQwUXfDdMoVB_dwVEfAUY0iUF2Y3zOdkmmIO9NGcJnEDRDxjAB9EMPaMAGVWHcePU-jUVXVTY9ftZ3GfBGxSPOuWGCD2iQZgXfk7OgSivEyvmYSbNCsViYxyJdZ02uR8gcek46niOmCkqmi8NOuKdM-H4-RZDsNdRjt0fsGGssOBAOPIkw_Aaja4q98Via-Q?width=1920&height=984&cropmode=none)
   
   * Observar bem a posição do componente Error Viewer
   
   ![alt_tag](https://jjrjug-dm2305.files.1drv.com/y4mSa4QcUlZERCDxR1Gzi6kYXOc90o22ifAl_jJCnz20svBsRZuaU8pPMPFW2PqovrXoUJO9VLcXtRpLdubSyg1wTv_Ye_MR_e6GX4cKQ2rk71_MY7wTljHCZC85N91P6YGoSInuzhcHsnls-GfzwwCojxCxDel-L81yeH3tLzjVOXhSiAdj8V2KsWjXVJlISYoFn0y9JGbZ4Io9Yp-xGIkcQ?width=1254&height=898&cropmode=none)
   
   **Alterado em 23/01/2018 ( Fundo Branco e Cinza nos selections e botões com icones )**
   
   Exemplo de chamada no evento Start:
   
   ```
   lblIcon.Caption = PIcone.Udp('ico_direita', 'glyphicon glyphicon-floppy-disk')
	lblIconFechar.Caption = PIcone.Udp('ico_direita_preto', 'glyphicon glyphicon-share-alt')
	lblIconFecharVenda.Caption = PIcone.Udp('ico_direita', 'glyphicon glyphicon-floppy-disk')
	
	If &Mode = 'DLT'
		lblIconEliminar.Caption = PIcone.Udp('ico_direita_preto', 'glyphicon glyphicon-handshake-o')
		lblIconFecharVenda.Caption = ''
	Else
		lblIconEliminar.Caption = ''
	Endif
   ```
   
   >>As classes ico_direita , e ico_direita_preto apenas posicionam o icone a direita com textos brancos ou preto. Estão lá no Thema.
   
   
   
2. Padrão das TRANSACTIONS;

   ![alt_tag](https://hzr59a-dm2305.files.1drv.com/y4mv0xZK0g40k6FCu0cXth8tWt2UCPXgFhhOT1GGCBsLwsmT3Taiiun2boa5Q-O080QtkEgFrEEH7rV2Ck3wgpCy63o68TLdOUePlViGVSb2rFBeIZoG5_iY7nhFZuCe997A8OE-YbL5obwkzd7JRkh3ymBjsC5yhxvweNwQg7ByK2zG-36hmj5zJNOcdXxmUOuQoybmbxoAXK7KbBh7ocSVw?width=1920&height=984&cropmode=none)

3. Padrão dos Prompts;

   ![alt_tag](https://jjrtug-dm2305.files.1drv.com/y4mKWDq9N_ng4XvMjXb5wKX4fd5XYlly9X9RGveDQwoellSrMrbTLHQLm6oGF17WMpjAgS3U6eC0cnfwLwp2543OW2B4oSZ7sHX-nNfTTPtnjmEpK8WXc6eSP60D7f4IHHxE_k07tQh3YQkuP8kn8tEb7Z71DbEHV1c7K9rzjvawB81XxMOKROW-Olspr1TSCHW-sfTt8986Yao6M_poh2Qww?width=934&height=636&cropmode=none)

4. Padrão de Webpanels;

   ![alt_tag](https://hzr89a-dm2305.files.1drv.com/y4mI4RAYDYsZ78eHOiQyckcuWOFV3e8LL57eXvTpCDgC421nxsPfiqKwy_DgcfUpF5jZvF9HG7bPr3mgkmEBLZcxWomQ2DDvugBoPUkrk2hXCl15TzI841gA7iHfdWZKhoYCy33v_Y9f97OBJnj8XsTEtmVNE9nnB2JNb_PzfA974kiEr1P7FuB44udnqdzIYoJb5GX1MRGCJPjxU4zCPtTJg?width=915&height=917&cropmode=none)

5. Padrão dos Relatórios;

6. Padrão dos Menus;

7. Principais Classes utilizadas;

8. Fontes e components CSS/JAVASCRIPT utilizados;

