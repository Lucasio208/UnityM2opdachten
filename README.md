# UnityM2opdachten

array opracht 
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
