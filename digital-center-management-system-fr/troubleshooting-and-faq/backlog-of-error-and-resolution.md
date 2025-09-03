---
hidden: true
---

# Backlog of error and resolution



```
Error:
Odoo Server Error
 
Traceback (most recent call last):
  File "/usr/lib/python3/dist-packages/odoo/addons/base/models/ir_http.py", line 237, in _dispatch
    result = request.dispatch()
  File "/usr/lib/python3/dist-packages/odoo/http.py", line 696, in dispatch
    result = self._call_function(**self.params)
  File "/usr/lib/python3/dist-packages/odoo/http.py", line 370, in _call_function
    return checked_call(self.db, *args, **kwargs)
  File "/usr/lib/python3/dist-packages/odoo/service/model.py", line 94, in wrapper
    return f(dbname, *args, **kwargs)
  File "/usr/lib/python3/dist-packages/odoo/http.py", line 358, in checked_call
    result = self.endpoint(*a, **kw)
  File "/usr/lib/python3/dist-packages/odoo/http.py", line 919, in __call__
    return self.method(*args, **kw)
  File "/usr/lib/python3/dist-packages/odoo/http.py", line 544, in response_wrap
    response = f(*args, **kw)
  File "/usr/lib/python3/dist-packages/odoo/addons/web/controllers/main.py", line 1374, in call_button
    action = self._call_kw(model, method, args, kwargs)
  File "/usr/lib/python3/dist-packages/odoo/addons/web/controllers/main.py", line 1362, in _call_kw
    return call_kw(request.env[model], method, args, kwargs)
  File "/usr/lib/python3/dist-packages/odoo/api.py", line 404, in call_kw
    result = _call_kw_multi(method, model, args, kwargs)
  File "/usr/lib/python3/dist-packages/odoo/api.py", line 391, in _call_kw_multi
    result = method(recs, *args, **kwargs)
  File "/usr/lib/python3/dist-packages/odoo/addons/repair/models/repair.py", line 510, in action_repair_end
    vals['move_id'] = repair.action_repair_done().get(repair.id)
  File "/mnt/extra-addons/icrc_repair/models/repair.py", line 302, in action_repair_done
    'owner_id': owner_id,
Exception
 
The above exception was the direct cause of the following exception:
 
Traceback (most recent call last):
  File "/usr/lib/python3/dist-packages/odoo/http.py", line 652, in _handle_exception
    return super(JsonRequest, self)._handle_exception(exception)
  File "/usr/lib/python3/dist-packages/odoo/http.py", line 317, in _handle_exception
    raise exception.with_traceback(None) from new_cause
UnboundLocalError: local variable 'owner_id' referenced before assignment
```

repair -> the product repaired has the wrong owner id or the product is not in the stock "Repair" anymore&#x20;

