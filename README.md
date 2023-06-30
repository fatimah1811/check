@check50.check()
def test1():
"""respond to name Faith"""
check50.run("./hello").stdin("Faith").stdout("Faith").exit(0)
