# Version_code

Marques Benjamin, v1, 06/07/2023

def test_different():
    # Test case 1: n1, n2 et n3 sont tous égaux
    assert different(1, 1, 1) == "trois égaux"

    # Test case 2: n1 et n2 sont égaux, n3 est différent
    assert different(2, 2, 3) == "deux égaux"

    # Test case 3: n1 et n3 sont égaux, n2 est différent
    assert different(4, 5, 4) == "deux égaux"

    # Test case 4: n2 et n3 sont égaux, n1 est différent
    assert different(6, 7, 7) == "deux égaux"

    # Test case 5: n1, n2 et n3 sont tous différents
    assert different(8, 9, 10) == "tous différents"

test_different()
