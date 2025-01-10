# How to add getter and setter method for TypeScript in VSC?
1. Install [`TypeScript GetSet` plugin](https://marketplace.visualstudio.com/items?itemName=z0gSh1u.vscode-ts-getset#:~:text=Launch%20VS%20Code%20Quick%20Open%20%28Ctrl%2BP%29%2C%20paste%20the,cursor%20at%20the%20first%20line%20of%20class%20declaration.) in VSC marketplace.
2. Move the cursor to the begin of class definition. As red arrow points in the following figure.

<img width="325" alt="image" src="https://github.com/user-attachments/assets/f2e39b5d-b29c-4f8b-9df2-e268cee40fb3" />

3. execute `> vscode-ts-getset: Generate Getter & Setter` command in VSC search box (which at menu bar). Shown as following figure.   

<img width="462" alt="image" src="https://github.com/user-attachments/assets/8f43611e-ffe1-4f80-a7ad-270f6ea44986" />

4. That's done.

> [!NOTE]
> private member must start with `_`. Otherwise, it will throw an error when executing `> vscode-ts-getset: Generate Getter & Setter`.

> [!NOTE]
> The cursor must at begin of class definition. Otherwise, it will also throw an error when executing `> vscode-ts-getset: Generate Getter & Setter`.
 
