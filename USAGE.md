<!-- Start SDK Example Usage [usage] -->
```python
import speakeasybar
from speakeasybar.models import shared

s = speakeasybar.Speakeasybar()


res = s.drinks.list_drinks(drink_type=shared.DrinkType.SPIRIT)

if res.classes is not None:
    # handle response
    pass

```
<!-- End SDK Example Usage [usage] -->