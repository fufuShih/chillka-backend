��#   c h i l l k a - b a c k e n d 
 
 # #   P r o j e c t   O v e r v i e w 
 
 T h i s   p r o j e c t   i s   b u i l t   u s i n g   T y p e S c r i p t ,   E x p r e s s ,   a n d   M o n g o D B . 
 
 # #   P r o j e c t   S t r u c t u r e 
 
 T h e   p r o j e c t   f i l e s   a n d   d i r e c t o r i e s   a r e   o r g a n i z e d   a s   f o l l o w s : 
 
 ` ` ` 
 / r o o t 
 | - -   n o d e _ m o d u l e s / 
 |       | - -   ( a l l   m o d u l e s   i n s t a l l e d   b y   n p m ) 
 | 
 | - -   p u b l i c / 
 | 
 | - -   s r c / 
 |       | - -   r o u t e / 
 |       | - -   m i d d l e w a r e / 
 |       | - -   m o d e l / 
 |       | - -   s e r v i c e / 
 |       | - -   s w a g g e r / 
 |       | - -   t y p e / 
 |       | - -   u t i l / 
 | 
 | - -   . e n v   ( e n v i r o n m e n t   v a r i a b l e s ) 
 | - -   a p p . j s   ( m a i n   a p p l i c a t i o n   f i l e ) 
 | - -   p a c k a g e . j s o n 
 ` ` ` 
 
 # #   H o w   t o   D e v ? 
 
 T o   r u n   t h e   p r o j e c t   t o   d e v ,   e x e c u t e   t h e   f o l l o w i n g   c o m m a n d s   i n   t h e   t e r m i n a l : 
 
 1 .   * * A d d i n g   E n v i r o n m e n t   V a r i a b l e s * * : 
 
       1 - 1 .   * * D u p l i c a t e   ` . e n v . e x a m p l e `   a n d   r e n a m e   t o   ` . e n v `   f i l e * * 
 
       1 - 2 .   * * D e f i n e   V a r i a b l e s * * :   A d d   v a r i a b l e s   o n   n e w   l i n e s   i n   t h e   f o r m a t   ` K E Y = V A L U E ` ,   f o r   e x a m p l e : 
 
       ` ` ` p l a i n t e x t 
       M O N G O D B _ U R L = m o n g o d b : / / u s e r n a m e : p a s s w o r d @ l o c a l h o s t : 2 7 0 1 7 / d a t a b a s e 
       P O R T = 8 0 0 0 
       N O D E _ E N V = d e v e l o p m e n t 
       ` ` ` 
 
 2 .   * * ( O p t i o n a l )   I f   y o u   d o n ' t   h a v e   M o n g o D B ,   y o u   c a n   u s e   D o c k e r   t o   a d d   i t * * : 
 
       ` ` ` b a s h 
       d o c k e r - c o m p o s e   - f   d o c k e r - c o m p o s e . d e v . y m l   u p 
       / /   m o d i f y   t h e   . e n v 
       M O N G O D B _ U R L = m o n g o d b : / / r o o t : e x a m p l e @ l o c a l h o s t : 2 7 0 1 7 / ? a u t h S o u r c e = a d m i n 
       ` ` ` 
 
 3 .   * * I n s t a l l   D e p e n d e n c i e s * * : 
       ` ` ` b a s h 
       y a r n   i n s t a l l 
       ` ` ` 
 4 .   * * S t a r t   t h e   S e r v e r * * : 
       ` ` ` b a s h 
       y a r n   d e v 
       ` ` ` 
 
 M a k e   s u r e   y o u r   M o n g o D B   s e r v i c e   i s   u p   a n d   r u n n i n g   b e f o r e   s t a r t i n g   t h e   a p p ,   e s p e c i a l l y   i f   i t   i s   b e i n g   r u n   l o c a l l y . 
 
 # #   D o c u m e n t a t i o n 
 
 U s e   S w a g g e r   f o r   A P I   d o c u m e n t a t i o n ,   c h e c k   o n   ` s c h e m a G e n e r a t o r . j s `   f o r   m o r e   d e t a i l e d   s c r i p t s . 
 
 1 .   * * G e n e r a t e   S c h e m a s * * 
 
 P l e a s e   e n s u r e   k e e p i n g   a l l   t h e   t y p e s   i n   ` s r c / t y p e `   f o l d e r   t o   b u i l d   t h e   s c h e m a s   i n s i d e   ` s r c / s w a g g e r / b u i l d ` . 
 
 ` ` ` b a s h 
 #   A u t o g e n e r a t e   s w a g g e r - o u t p u t . j s o n 
 y a r n   s w a g g e r 
 
 ` ` ` 
 
 2 .   * * A d d   S w a g g e r   C o m m e n t s * * 
 
 U s e   s w a g g e r   2 . 0   f e a t u r e s ,   c h e c k   o n   [ d o c u m e n t ] ( h t t p s : / / s w a g g e r - a u t o g e n . g i t h u b . i o / d o c s / s w a g g e r - 2 / )   f o r   m o r e   d e t a i l s . 
 
