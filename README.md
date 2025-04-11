# pythonPlaywright
I will be working on playwright web automation using python.

We can also provide run time argument

pytest filename.py --headed
                   --base-url https://saucedemo.com
                   --browser chromium
                   --browser firefox

If wanted to skip any test in particular browser
@pytest.mark.skip_browser("firefox")

If wanted to run only in chromium browser
@pytest.mark.only_browser("chromium")

--tracing retain-on-failure
--tracing on

playwright show-trace location of trace