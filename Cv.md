Вот приведенный текст в формате Markdown:

# My CV

## Maxim Kiselev
Student of group PIR-221

Contacts:


My goals:
- Create game company
- Learn programming
- Build a house in mountains

## Education
- Place of studying: Belarusian-Russian University
- Years of studying: 2020-n.d
- Degree name: Bakalavr

Advantages:
- Assudity
- Responsibility
- Stress resistance
- Team building

## My Projects
- UnityMedievalCardGame
- UnrealEngineGame: BigFile

## Experience of Work
- [My Freelance Page](My_Freelance_Page_URL)

## English Language
- B2 level, finish courses in English School

## Example of Code

```csharp
public delegate void TransformChangeDelegate(GameObject target);
public IEnumerator SmoothTransformRotationChange(float speed, float duration, Vector3 startPos, Quaternion startRot, GameObject target)
{
    target.GetComponent().enabled = false;
    while (Vector3.Distance(target.transform.position, startPos) > 0.01 || Quaternion.Angle(target.transform.rotation, startRot) > 0.1)
    {
        speed += Time.deltaTime / duration;
        target.transform.position = Vector3.Lerp(target.transform.position, startPos, speed);
        target.transform.rotation = Quaternion.Lerp(target.transform.rotation, startRot, speed);
        TransformDelegate?.Invoke(target);
        yield return null;
    }
    target.GetComponent().enabled = true;
}
```

Контактная информация: