# ICU_Dictionary
Creation of Identifier Dictionary for ICU terms and prototype to apply it.

# **DLP Classification**  

| **Category**                     | **Data Points (Brazilian_ Portuguese)**                                       | **DLP Sensitivity Level** | **Potential Risks**                                  |
|-----------------------------------|------------------------------------------------------|---------------------------|-----------------------------------------------------|
| **Patient Identifiers (PHI)**     | Nome, Nº Atendimento, Nº Prontuário, Data Nascimento | 🔴 High (PII/PHI)         | Identity theft, unauthorized access               |
| **Hospitalization Data**          | DIH (Data da Internação Hospitalar), DUTI (Data da Admissão na UTI), LEITO                                    | 🟠 Medium                 | Exposure of admission dates could violate privacy |
| **Insurance & Financial Data**    | Convênio, Seguro de saúde                                          | 🔴 High                   | Insurance fraud, financial abuse                  |
| **Clinical & Medical Data**       | Diagnósticos, História Clínica, Ex Físico, Impressão Evolutiva | 🔴 High (Sensitive PHI) | Misuse of medical history, blackmail risks       |
| **Medication & Treatment**        | Prescrição, Antibióticos, Drogas em BIC            | 🔴 High (PHI)             | Prescription data leaks (e.g., opioids, controlled substances) |
| **Vital Signs & Monitoring**      | Sinais Vitais, Parâmetros Ventilatórios            | 🟠 Medium                 | Exposure could lead to manipulation of health status data |
| **Medical Devices & Procedures**  | Dispositivos Invasivos                              | 🟠 Medium                 | Security risk if combined with patient identifiers |
| **Medical Actions & Notes**       | Condutas                                           | 🟠 Medium                 | Internal procedures could reveal treatment plans |
| **Laboratory Data**               | Labs                                               | 🔴 High (PHI)             | Lab results often contain highly sensitive health markers |
| **Dietary Information**           | Dieta                                              | 🟡 Low                    | Less critical but still part of patient records  |


