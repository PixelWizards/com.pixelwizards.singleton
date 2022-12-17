## com.pixelwizards.singleton

A simple singleton that wraps the Unity MonoBehaviour base class.

Example:

public class MySingleton: Singleton<MySingleton>
{
		public void DoSomething()
		{
		}
}

You can now reference the singleton via it's instance like so:

`MySingleton.Instance.DoSomething();`

If the instance exists it will return a reference, if not it will be instantiated in the scene automatically. 