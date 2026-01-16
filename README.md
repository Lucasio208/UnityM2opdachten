# UnityM2opdachten

array opracht 1
![ezgif-4398ec5028dc0172](https://github.com/user-attachments/assets/c4e8dd83-3035-4bbc-a1f9-51dcf9c5ff86)

using UnityEngine;

public class array : MonoBehaviour
{
    [SerializeField] string[] Items;
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        if(Input.GetKeyDown(KeyCode.Return))PrintRandomItem();
        if(Input.GetKeyDown(KeyCode.Escape))PrintAllItems();
    }

    private void PrintRandomItem()
    {
        int i = Random.Range(0, Items.Length);
        Debug.Log(Items[i]);
    }

    private void PrintAllItems()
    {
        for (int i = 0; i < Items.Length; i++)
        {
            Debug.Log(Items[i]);
        }
    }
}


collision en forces opdracht 2
![Bezig met opnemen 2025-12-04 140017](https://github.com/user-attachments/assets/6821b48b-b36b-41ae-96f9-6451d34b4b7c)


M2 GDV les 2.2 (CODE) Peggle Game, Mikken, Schieten en Line Rendering
![video2gifs_qcudqe](https://github.com/user-attachments/assets/b517f480-538c-48a6-8074-99ebaf58ebb2)


M2 GDV les 3.2 bumpers en combo systeem 

![Bezig met opnemen 2025-12-11 141647](https://github.com/user-attachments/assets/2d4a7756-e99e-4ac8-ac85-7bc961916c17)

M2 GDV les 4.1 Leveldesign

<img width="1918" height="936" alt="image" src="https://github.com/user-attachments/assets/30b06bb6-6190-4895-b8fd-5cfbd65289b9" />

M2 GDV les 4.2 Codes versturen naar UI
![Bezig met opnemen 2026-01-16 172310 (1)](https://github.com/user-attachments/assets/70428d29-4534-4106-b586-b7a7c601c1db)

M2 GDV les 5.2 particle system

![Bezig met opnemen 2026-01-16 172310 (1)](https://github.com/user-attachments/assets/98c5825a-282a-43f1-94c5-46e38f55af7e)



