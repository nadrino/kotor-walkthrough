# Knights of the Old Republic II - Guide Index

[< Back to the README](../../../README.md)

## Walkthrough list

| Portrait                            | Name                                                 | Alignment      | Gender | Revan    | Description                                                                                                                                                                                                                                         |
|-------------------------------------|------------------------------------------------------|----------------|--------|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![po_pfhc05.jpg](img/po_pfhc05.jpg) | **[Meetra Surik (Canon)](00_LS_Temperate/index.md)** | LS - temperate | Woman  | LS/Man   | While loyal to Jedi ideals, Meetra does not follow them blindly. Her exile has tempered her once-idealistic faith into quiet pragmatism. She resists falling into the Sith’s hunger for domination, but she also questions the Council’s passivity. |
| ![po_PMHC04.jpg](img/po_PMHC04.jpg) | **Teren Voss**                                       | DS - temperate | Man    | DS/Woman | Male Exile, dark side–leaning but thoughtful. Falls for Kreia’s teachings but shows restraint.                                                                                                                                                      |
| ![po_PMHB10.jpg](img/po_PMHB10.jpg) | **Cael Doran**                                       | LS - strict    | Man    | DS/Man   | A devoted ex-Jedi who remained loyal even after exile. Seeks redemption through service, not rebellion.                                                                                                                                             |
| ![po_PFHC02.jpg](img/po_PFHC02.jpg) | **Sevra Korr**                                       | DS - strict    | Man    | LS/Woman | Exiled with bitter contempt. Views the Jedi as weak. Ruthless, focused, and sees power as the only truth. Will betray even allies to become Sith.                                                                                                   |
| ![po_PMHA05.jpg](img/po_PMHA05.jpg) | **Aven Sarek**                                       | Neutral        | Man    | LS/Woman | Seeks truth beyond doctrine. Rejects Jedi rigidity and Sith hunger. Makes choices situationally, sometimes selfish, sometimes selfless.                                                                                                             |



[< Back to the README](../../../README.md)

## Notes

### Mandalore

```
Modules/303nar/mandlead.dlg a_mands_leave(1);a_influence_inc(2, 2) 123405 onChoiceScript
Modules/502ond/mp_anda.dlg a_influence_inc(2, 2) 90577 onChoiceScript
Modules/502ond/mp_ponla.dlg a_influence_inc(2, 2) 90687 onChoiceScript
Modules/503ond/kavar.dlg a_lightsml();a_influence_inc(2) 119108 onChoiceScript
Modules/506ond/vaklu.dlg a_influence_inc(2, 3) 92255 onChoiceScript
Modules/511ond/tobin.dlg a_influence_inc(2, 1) 92482 onChoiceScript
Modules/511ond/tobin.dlg a_influence_inc(2, 2) 92483 onChoiceScript
Modules/605dan/mand.dlg a_influence_inc(2, 2) 123442 onChoiceScript
override/000react.dlg a_global_set("000_R_Psychotic_Mand");a_influence_inc(2, 1) 109472 onChoiceScript
override/000react.dlg a_global_set("000_R_Psychotic_Mand", 2);a_influence_inc(2, 1) 109473 onChoiceScript
override/000react.dlg a_global_set("000_R_Psychotic_Mand", 1);a_influence_inc(2, 1) 109474 onChoiceScript
override/000react.dlg a_influence_inc(2, 1) 50093 onChoiceScript
```
