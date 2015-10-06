# Coffee rules

```python
def coffee_rules():
    """
    Coffee rules for the coffee maker at the ISI room.
    """
    while(True):
        if (time.time() < datetime.time(14, 00)) and (coffee_level < 0.1):
            restart_coffee_maker()
        else:
            power_off_coffee_maker()
            empty_coffee_pot()
            fill_some_water_in_the_coffee_pot()
```
