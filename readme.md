Object pool

How to use:
1. Add to instantiated object script PoolItem
2. Instead of Instantiate() use Pool.Instance.Get(originalGameObject, position, rotation)
3. Instead of Destroy(gameObject) use Pool.Instance.Destroy(gameObject)
