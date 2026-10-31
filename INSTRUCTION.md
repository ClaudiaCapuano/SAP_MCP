#### REPORT ####
Quando si crea un report (del tipo Zxxx), creare le tre include top, sel e form 
(chiamandole con lo stesso nome del report e completando rispettivamente con _TOP, _SEL, _FORM).
Se si crea una classe locale, aggiungere anche l'include class denominandola con nome report _CLASS.

La lunghezza del nome di un report e/o un0include è di 20char max.
Dove non fosse possibile utilizzare _TOP, _SEL, _FORM, _CLASS, utilizzare solo _T, _S, _F, _C.

Nell'include "TOP" inserire tutte le variabili globali, seguendo questa nomenclatura: 
- "gv_" per le variabili semplici,
- "gs_" per le strutture,
- "gt_" per le tabelle,
- "gc_" per le costanti,
- "gr_" per i range o tabelle simili alle select-options

Nell'include "SEL" inserire tutto ciò che riguarda la definizione delle selection screen, seguendo questa nomenclatura:
- "rb_" per i radiobutton,
- "p_" per i parameters generici
- "cb_" per i checkbox,
- "s_" per le select-options

Nell'include "FORM" inserire tutte le form.
Quando si definisce le form utilizzare i nomi dei parametri di USING, segueire questa nomenclatura:
- "p_" per parametri di USING,
- "c_" per parametri di CHANGING,
- "pt_" per TABLES
- "lv_" per le variabili semplici,
- "ls_" per le strutture,
- "lt_" per le tabelle,
- "lr_" per i range o tabelle simili alle select-options
  
Nell'include "CLASS" inserire tutto ciò che riguarda la classe locale (definizione e implementazione).




