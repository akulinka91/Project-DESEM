To open the plug-in first click File-New-Other-Multi-page Editor file, then choose container and click Finish.
1. Copying
Use the command "copy [existing_machine_name] [created_machine_name]" on the first tab of the editor to copy existing machine. 
There is a machine names verification in the plug-in. First machine should exist in the container and second machine should not exist.
The result of the copying could be find at the second page of the editor.
If user input is correct, new machine will be created. To see it, please refresh container in the Event-B Explorer tree.
2. Renaming
There are two variants of renaming - renaming of the machine/context and renaming of their elements (variants, events, axioms, etc.)
To rename machine/context type "[machine_old_name/context_old_name] with [machine_new_name/context_new_name]"
Make sure, that the first name exists in the model, while the second one does not exist.
To rename element inside machine/context tyoe "[machine/context] [element_old_name] with [element_new_name]"
Make sure, that first two names exist in the model, while the third one does not exist. element_new_name should not be null as well.
The new name will appear in the model as soon as command will be executed.
The result of the renaming could be find at the second page of the editor.
3. Merging
To merge two machines, use the command "[machine_1] and [machine_2]"
Make sure that both machines exist in the model.
Pay attention on the fact that created composition will be saved in the first machine. If you need to keep this machine in the model, copy it first.
The result of the merging could be find at the second page of the editor.