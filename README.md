# Simple C++ RingBuffer

- pure C++, no dependency
- cross platform
- single header file

## Example

``` C++
    Buffers::RingBuffer<int> ringBuffer(8);
    for( int i = 0; i < 4; ++i )
    {
        ringBuffer.add( i );
    }

    // Print RingBuffer with iterator
    for(auto it = ringBuffer.begin(); it != ringBuffer.end(); it++) {
        cout << *it << endl;
    }
```

## TODO
- implement pop_front, front, back functions
- make it thread safety, like lock free implementation
- add tests 
