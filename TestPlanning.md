# Test cases

SINGLE:
    - For the first time the primary store is fired
    - Torpedo stores are fired alternating
    - If the store next in line is empty, the ship tries to fire the other store
    - If the fired store reports a failure, the ship does not try to fire the other one

ALL:
    - tries to fire both of the torpedo stores.