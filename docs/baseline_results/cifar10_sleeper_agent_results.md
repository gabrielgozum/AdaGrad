# Cifar10 Sleeper Agent Baseline Evaluation

Results obtained using Armory 0.16.0

## Undefended

**accuracy_on_benign_test_data_source_class**

|Poison percentage                         |run1  |run2  |run3  |**mean**  |std   |
|------------------------------------------|------|------|------|------|------|
|0                                         |0.871 |0.881 |0.876 |**0.876** |0.004 |
|1                                         |0.882 |0.895 |0.88  |**0.886** |0.007 |
|5                                         |0.878 |0.893 |0.894 |**0.888** |0.007 |
|10                                        |0.879 |0.882 |0.881 |**0.881** |0.001 |
|20                                        |0.882 |0.871 |0.879 |**0.877** |0.005 |
|30                                        |0.88  |0.878 |0.87  |**0.876** |0.004 |
|50                                        |0.889 |0.881 |0.875 |**0.882** |0.006 |


**accuracy_on_benign_test_data_all_classes**

|Poison percentage                         |run1  |run2  |run3  |**mean**  |std   |
|------------------------------------------|------|------|------|------|------|
|0                                         |0.852 |0.849 |0.845 |**0.849** |0.003 |
|1                                         |0.852 |0.852 |0.849 |**0.851** |0.002 |
|5                                         |0.849 |0.851 |0.85  |**0.85**  |0.001 |
|10                                        |0.852 |0.848 |0.843 |**0.848** |0.004 |
|20                                        |0.841 |0.847 |0.845 |**0.845** |0.002 |
|30                                        |0.843 |0.841 |0.84  |**0.841** |0.001 |
|50                                        |0.841 |0.84  |0.844 |**0.842** |0.001 |


**attack_success_rate**

|Poison percentage                         |run1  |run2  |run3  |**mean**  |std   |
|------------------------------------------|------|------|------|------|------|
|0                                         |-     |-     |-     |**-**     |-     |
|1                                         |0.99  |0.817 |0.077 |**0.628** |0.396 |
|5                                         |0.917 |0.913 |0.866 |**0.899** |0.023 |
|10                                        |0.979 |0.451 |0.586 |**0.672** |0.224 |
|20                                        |0.86  |0.987 |0.713 |**0.853** |0.112 |
|30                                        |0.617 |0.744 |0.868 |**0.743** |0.102 |
|50                                        |0.935 |0.598 |1     |**0.844** |0.176 |


**accuracy_on_poisoned_test_data_all_classes**

|Poison percentage                         |run1  |run2  |run3  |**mean**  |std   |
|------------------------------------------|------|------|------|------|------|
|0                                         |-     |-     |-     |**-**     |-     |
|1                                         |0.764 |0.762 |0.761 |**0.762** |0.001 |
|5                                         |0.762 |0.762 |0.761 |**0.761** |0     |
|10                                        |0.764 |0.76  |0.754 |**0.759** |0.004 |
|20                                        |0.753 |0.76  |0.766 |**0.76**  |0.005 |
|30                                        |0.755 |0.753 |0.753 |**0.754** |0.001 |
|50                                        |0.752 |0.752 |0.756 |**0.754** |0.002 |


## Perfect Filter

Coming soon


## Random Filter

Coming soon


## Activation Defense

Coming soon


## Spectral Signatures Defense

Coming soon