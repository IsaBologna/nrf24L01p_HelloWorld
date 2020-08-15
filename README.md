# nRF24L01p Mbed OS example

Exemplo baseado no Hello World da biblioteca [nRF24L01P by Owen Edwards](https://os.mbed.com/users/Owen/code/nRF24L01P/). 

O Hello World original dessa biblioteca usa uma versão descontinuada do MbedOS (OS 2), e por isso não é compatível com o Mbed Studio, só com compilador online e o CLI.

Para tornar o exemplo compatível com o Mbed Studio foram adaptadas as *comunicações seriais* para a API OS 6.2. 

## Mbed Studio

Importar o projeto diretamente do github: 
```
File > Add Library to Active Program...
```

Escolhendo a devBoard em **target** a IDE identifica a pinagem, e assim não aponta erros. 

## FRDM-KL25Z

Para usar a frdm com o MS, o firmware precisa ser atualizado para o [DAPLink](open_sda_bin/k20dx_frdmkl25z_if_crc.bin) ao invés do [P&EMicro](open_sda_bin/MSD-DEBUG-FRDM-KL25Z_Pemicro_v118.SDA). 

Com o firmware atualizado e os drivers instalados, o Mbed Studio deve identificar a placa automaticamente. E uma serial aparece no terminal (normlmente, na parte inferior da IDE).