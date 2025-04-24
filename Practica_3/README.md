Practica 3

Esta práctica de laboratorio se centró en el análisis y la transformación de señales de radiofrecuencia (RF) a su representación en envolvente compleja (EC) mediante el uso de GNU Radio. Se abordaron distintos esquemas de modulación digital —OOK (On-Off Keying), BPSK (Binary Phase Shift Keying) y FSK (Frequency Shift Keying)— con el objetivo de comparar su comportamiento tanto en RF como en EC.

Se desarrollaron flujogramas específicos para cada técnica de modulación, permitiendo la visualización y análisis de las señales en los dominios del tiempo, la frecuencia y el plano de constelación. A través de estos ejercicios se evidenció cómo la EC, al representar la señal en banda base con sus componentes ortogonales I y Q, facilita operaciones como la demodulación, análisis espectral y visualización de símbolos con mayor eficiencia y claridad que su equivalente en RF.

Además, se realizó una revisión técnica y funcional de bloques personalizados utilizados para la conversión y modulación: e_RF_VCO_ff y e_EC_VCO_fc.

La práctica incluyó pruebas controladas para observar cómo variaciones en parámetros como la frecuencia portadora o la desviación de frecuencia afectan la señal modulada. En el caso de FSK, por ejemplo, se evaluaron distintos escenarios para entender la relación entre desviación de frecuencia y la separación entre símbolos en el plano de constelación.
