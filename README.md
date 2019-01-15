# Vaja4-interrupt-button-STM32F0
Modra tipka utripi pravilno po navodilih, zelena tipka pa ne dela
ODGOVORI:
 2. B.) Gpio_EXTI0 = PA0 , PC9 = zelena led, PC8 = modra LED. 
 3. c.) HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9); 
    d.) <100ms.
    e.) HAL_GPIO_TogglePin(GPIOC,GPIO_PIN_8); 
    f.) HAL_Delay(500); 
 4. b.)Ko pritisnemo Blue PushButton se prižge zelena LED, modra LED pa ves čas utripa . 
    c.)Pritisk modre tipke ne vpliva na utripanje modre LED
    
KOMENTAR: Pritisk na tipko PA0 prižge zeleno LED, medtem ko modra LED ves čas utripa.
