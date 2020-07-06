# bitrix-notes

## Выбрать чекбокс (поставить галку)
Нужно получить ID значения которое нужно выбрать
```php
$enum = CIBlockPropertyEnum::GetList(Array("DEF"=>"DESC", "SORT"=>"ASC"), Array("IBLOCK_ID"=>$iblock_id_feature, "CODE"=>"IS_SOON"))->GetNext();
```
