# Item Hooks

## OnItemAdded

``` csharp
void OnItemAdded(Inventory inventory, int slot, IInventoryItem item)
{
    Puts("OnItemAdded works!");
}
```

``` javascript
We need a JavaScript example here
```

``` lua
We need a Lua example here
```

``` python
We need a Python example here
```

 * Called from Inventory.ItemAdded
 * No return behavior
 * Called when an item was added to an inventory

## OnItemRemoved

``` csharp
void OnItemRemoved(Inventory inventory, int slot, IInventoryItem item)
{
    Puts("OnItemRemoved works!");
}
```

``` javascript
We need a JavaScript example here
```

``` lua
We need a Lua example here
```

``` python
We need a Python example here
```

 * Called from Inventory.ItemRemoved
 * No return behavior
 * Called when an item was removed from an inventory
 
## OnItemDeployed

``` csharp
void OnItemDeployed(DeployableObject deployable, NetUser netuser)
{
    Puts("OnItemDeployed works!");
}
```

``` javascript
We need a JavaScript example here
```

``` lua
We need a Lua example here
```

``` python
We need a Python example here
```

 * Called from DeployableItemDataBlock.DoAction1
 * No return behavior
 * Called when an item was deployed by a player
