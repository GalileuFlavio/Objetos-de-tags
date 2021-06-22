public class FindObject : MonoBehaviour
{
    public GameObject[] enemies;

    void Start()
    {
        enemies = GameObject.FindGameObjectsWithTag("Enemy");
    }
}
