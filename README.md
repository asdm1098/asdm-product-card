# ASDM-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### A Stiven Diaz M

## Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'asdm-product-card';
```

```
<ProductCard 
    product={ product } 
    initialValues={{
        count: 4,
        maxCount: 10
    }}
>   
    {
        ( {reset, maxCount,increaseBy, count, isMaxCountReached} ) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```