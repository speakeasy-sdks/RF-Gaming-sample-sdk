<!-- Start SDK Example Usage [usage] -->
```python
import speakeasybar
from speakeasybar.models import shared

s = speakeasybar.Speakeasybar(
    security=shared.Security(
        api_key="<YOUR_API_KEY_HERE>",
    ),
)


res = s.drinks.list_drinks(drink_type=shared.DrinkType.SPIRIT)

if res.classes is not None:
    # handle response
    pass
```
<!-- End SDK Example Usage [usage] -->