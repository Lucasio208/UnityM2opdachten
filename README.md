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


